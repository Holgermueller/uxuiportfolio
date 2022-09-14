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
        <p class="headline text-center">
          Fans of this kind of music face three problems:
        </p>
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
        <v-flex xs12 sm12 md6 lg4 xl4>
          <div class="illustration-info">
            <p>
              The integrated map allows users to find a given show's venue
              without having to use another app.
            </p>
            <p>
              The integrated map also allows users to input their point of
              departure, because they may not be leaving from the spot where
              they were when they bought their tickets.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg4 xl4>
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
        <v-flex xs12 sm12 md6 lg4 xl4>
          <div class="illustration-info">
            <p>
              In addition to making the app easier to use, the profile feature
              makes using FTS a more-personal experience.
            </p>
            <p>
              The integrted translation feature ensures users don't have to rely
              on another app to use this one.
            </p>
          </div>
        </v-flex>
      </v-layout>
    </v-container>

    <v-img
      class="my-4 align-end text-center"
      src="./alllofidemo.png"
      height="300px"
    >
      <p>
        The user flow centers on finding tickets and information on the show the
        user wishes to attend.
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

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          A usability study revealed further tweeks needed to be made to the
          app.
        </p>
      </section>
    </div>

    <v-img height="609px" width="312px" src="./processingpng.png"></v-img>

    <v-img
      class="full"
      height="609px"
      width="312px"
      src="./hifipay.png"
    ></v-img>

    <v-btn text> <v-icon left>mdi-arrow-up</v-icon> Back to top</v-btn>
  </div>
</template>

<script>
export default {
  name: 'FirstCaseStudy',
}
</script>

<style scoped>
a {
  text-decoration: none;
}
h1,
h2 {
  text-align: center;
  margin: 4px auto;
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
}
.figma-link {
  text-align: center;
}
.v-btn {
  margin: auto;
}
</style>
