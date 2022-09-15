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
