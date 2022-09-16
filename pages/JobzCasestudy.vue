<template>
  <div id="Jobz">
    <nuxt-link to="/Portfolio">
      <v-chip outlined>
        <v-icon left>mdi-arrow-left</v-icon>
        Back
      </v-chip>
    </nuxt-link>

    <h1 class="app-name display-4">Jobz</h1>
    <h2 class="display-2">Helping first-generation immigrants get hired.</h2>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          First-generation immigrants face many struggles when trying to find
          work, including but not limited to language barriers and unfamiliarity
          with their surroundings.
        </p>
        <p class="headline">
          Solution: Design an app that helps alleviate some of these struggles.
        </p>
      </section>
    </div>

    <v-img src="./jobsdeskhome.png"></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          I used various articles to gather information on the difficulties
          first-generation immigrants face while job hunting. I designed my
          solutions around the ones that could be most-easily solved with a
          mobile app and website.
        </p>
      </section>
    </div>

    <v-img height="1224" width="1632" src="./jobsideation.png"></v-img>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline">
          After some quick sketching, I decided the problems most easily
          addressed by an app are accessibility to resources and resume
          templating.
        </p>
      </section>
    </div>

    <v-container class="mx-auto my-4" fluid>
      <v-layout row wrap>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <div class="illustration-info mx-auto">
            <p>
              Initial designs for the Jobz mobile app focused on quick resume
              templateing for job seekers on the go.
            </p>
            <br />
            <p>
              Users, after setting up an initial resume, would be able to
              include features they deem necessary to applying to a given job,
              allowing them to easily tailor their resumes to specific job
              listings.
            </p>
          </div>
        </v-flex>
        <v-flex xs12 sm12 md6 lg6 xl6>
          <v-img
            src="./jobslofires.png"
            height="609px"
            width="312px"
            class="mx-auto"
          ></v-img>
        </v-flex>
      </v-layout>
    </v-container>

    <div class="flow-display">
      <v-img
        class="align-end text-center"
        src="./jobslofiflow.png"
        height="300px"
      >
        <p>
          I created a lo-fi prototype to see how if the user flow was intuitive
          enough.
        </p></v-img
      >
      <p class="title adobexd-link">
        You can see the Lo-Fi prototype
        <a
          href="https://xd.adobe.com/view/e6e29c80-a3f0-47b0-9fbe-e3367e43c572-b3b1/"
          target="_blank"
          >here</a
        >
      </p>
    </div>

    <div class="section-background">
      <section class="case-study-info">
        <p class="headline text-center">
          A remote usability study of five people uncovered three findings:
        </p>
        <v-container fluid>
          <v-layout row wrap>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">1</p>
              <p class="headline text-center">Better resources</p>
              <p class="problem">
                Users don’t just want contact info. To really help them,
                integrate a map or open to Google maps by clicking on the
                address.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">2</p>
              <p class="headline text-center">Ratings</p>
              <p class="problem">
                Users want to know more about a potential employer without
                having to comb the Internet.
              </p>
            </v-flex>
            <v-flex xs12 sm12 md6 lg4 xl4>
              <p class="headline text-center">3</p>
              <p class="headline text-center">Continuity</p>
              <p class="problem">
                Users at least wanted the option of beginning work on one
                platform and continuing on another.
              </p>
            </v-flex>
          </v-layout>
        </v-container>
      </section>
    </div>

    <v-btn class="my-16 mx-auto" @click="backToTop" text>
      <v-icon left>mdi-arrow-up</v-icon> Back to top</v-btn
    >
  </div>
</template>

<script>
export default {
  name: 'JobzPage',

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
  background-color: rgba(0, 120, 20, 0.5);
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
.adobexd-link {
  text-align: center;
}

.v-btn {
  display: block;
}
</style>
