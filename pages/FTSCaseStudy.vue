<template>
  <div id="FTSCaseStudy">
    <nuxt-link to="/Portfolio">
      <v-chip outlined>
        <v-icon left>mdi-arrow-left</v-icon>
        Back
      </v-chip>
    </nuxt-link>
    <h1 class="app-name display-4">FTS: Fearless Ticket Sellers</h1>
    <h2 class="display-2">The new way to experience underground music</h2>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          Traditionally, punk rock bands and other forms of underground music
          perform in unorthodox venues, like a friend's garage, someone's living
          room, or abandoned warehouses. Places you don't usually find through
          traditional ticket-sellers.
        </p>
        <p class="headline">
          Some light Googling revealed this leaves a huge gap in ticket selling.
          Fearless Ticket Sellers (FTS) seeks to bridge that gap.
        </p>
      </section>
    </div>

    <div class="case-study-header">
      <v-img
        class="full mx-auto"
        height="609px"
        width="312px"
        src="./fts.png"
      ></v-img>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <h3 class="headline text-center py-4">
          Fans of this kind of music face three problems:
        </h3>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">Time</p>
              <p class="problem">
                Users don’t have time to research every little thing about the
                particular show they’d like to attend.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">Location</p>
              <p class="problem">
                Users may have difficulty locating the site of the show they
                wish to attend.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">Language</p>
              <p class="problem">
                Users need the information to be presented to them in more than
                one language.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info mx-auto">
            <p>
              The integrated map allows users to find a given show's venue
              without having to waste time by going to another app.
            </p>
            <br />
            <p>
              The integrated map also allows users to input their point of
              departure, because they may not be leaving from the spot where
              they were when they bought their tickets.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./map.png"
            height="609px"
            width="312px"
            class="mx-auto"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container class="my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./profile.png"
            height="609px"
            width="312px"
            class="mx-auto"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info">
            <p>
              In addition to making the app easier to use, the profile feature
              makes using FTS a more-personal experience.
            </p>
            <br />
            <p>
              The integrted translation feature ensures users don't have to rely
              on another app to use this one, saving them that much time.
            </p>
          </div>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="flow-display">
      <v-img
        class="align-end text-center"
        src="./alllofidemo.png"
        height="300px"
      >
        <p>
          The user flow centers on finding tickets and information on the show
          the user wishes to attend.
        </p></v-img
      >
      <p class="title figma-link">
        You can see the Lo-Fi prototype
        <a
          href="https://www.figma.com/proto/f3AHbi9EVS9Z4VCKOgttPC/Home?node-id=2%3A4&scaling=scale-down&page-id=0%3A1&starting-point-node-id=2%3A4"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          A usability study revealed further tweaks needed to be made to the
          app.
        </p>
      </section>
    </div>

    <v-container class="my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            height="609px"
            width="312px"
            src="./processingpng.png"
            class="mx-auto"
          ></v-img>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info">
            <p>
              A processing screen or overlay of some kind lets users know
              something is happening.
            </p>
            <br />
            <p>
              They can rest assured their transaction went through, and don't
              have to wonder and worry.
            </p>
          </div>
        </v-flex>
      </v-layout>
    </v-container>

    <v-container class="my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info">
            <p>
              Little things like an option to remember their payment info lets
              users know they'll have an even quicker checkout the next time
              they use the app.
            </p>
            <br />
            <p>
              It's about getting them to want to use the app, not making them
              have to use the app.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            class="full mx-auto"
            height="609px"
            width="312px"
            src="./hifipay.png"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="flow-display">
      <v-img
        class="align-end text-center"
        src="./hifiprotofts.png"
        height="300px"
      >
        <p class="pt-8">
          The hi-fi prototype demonstrated a clearer user flow. It also meets
          user needs for quicker purchase and checkout.
        </p></v-img
      >
      <p class="title figma-link">
        Check out the Hi-Fi prototype
        <a
          href="https://www.figma.com/proto/f3AHbi9EVS9Z4VCKOgttPC/Home?node-id=76%3A218&scaling=scale-down&page-id=76%3A2&starting-point-node-id=76%3A218"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <h3 class="headline text-center py-4">Accessability Considerations</h3>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">1</p>
              <p class="problem">
                Larger buttons for users with some visual impairment,orthose who
                just have really big thumbs.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">2</p>
              <p class="problem">
                Integrated translation capabilities presents users with a
                more-personal experience.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">3</p>
              <p class="problem">
                Provided option for users to keep their credit card info saved
                to the app, should that be something the user wishes to do.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <section class="case-study-info">
      <h3 class="headline text-center py-4">Takeaways</h3>

      <h4 class="text-center my-12">Impact:</h4>
      <p class="problem">
        While not a social networking application, the integrated translation
        capability allows user to feel they are part of a larger community.
      </p>
      <p class="problem">
        The integrated map allows users to feel more connected to the area in
        which they live.
      </p>

      <h4 class="text-center my-12">What I learned:</h4>
      <p class="problem">
        I learned that the first idea is not always the best idea and to not be
        afraid to kill my darlings. Further iterations pointed out more ways to
        make FTS a great app.
      </p>
    </section>
    <p>hello</p>

    <v-img
      class="full mx-auto"
      height="609px"
      width="312px"
      src="./ftssuccess.png"
    ></v-img>

    <v-btn class="my-16 mx-auto" @click="backToTop" text>
      <v-icon left>mdi-arrow-up</v-icon> Back to top</v-btn
    >
  </div>
</template>

<script>
export default {
  name: 'FirstCaseStudy',
  methods: {
    backToTop() {
      window.scrollTo(0, 0)
    },
  },
}
</script>

<style scoped>
a {
  text-decoration: none;
}
h1,
h2 {
  text-align: center;
  margin: 4% auto;
}
.section-background {
  background-color: rgba(47, 158, 165, 0.5);
  border-radius: 5px;
}
.case-study-info {
  width: 85%;
  margin: 8% auto;
  padding: 8%;
}
.problem {
  width: 90%;
  margin: auto;
}
.illustration-info {
  margin: auto;
  width: 85%;
  padding: 2%;
  position: relative;
  top: 50%;
  -webkit-transform: translateY(-50%);
  -ms-transform: translateY(-50%);
  transform: translateY(-50%);
}
.flow-display {
  margin: 8% 0;
}
.figma-link {
  text-align: center;
}
.v-btn {
  display: block;
}
</style>
