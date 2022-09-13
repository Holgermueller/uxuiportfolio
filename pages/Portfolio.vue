<template>
  <div id="Portfolio">
    <v-card class="portfolio-card" elevation="0">
      <v-card-title><h1 class="display-4">Portfolio</h1></v-card-title>

      <v-card-text>
        <div class="project-even project-display">
          <v-img class="img-even" src="./fts.png"></v-img>

          <div class="project-text-even">
            <h2 class="project-title">Fearless Ticket Sellers</h2>
            <p>How do I purchase tickets for smaller, unorthodox venues?</p>
            <nuxt-link to="/FTSCaseStudy">
              <p class="title project-link">
                See case study <v-icon right>mdi-arrow-right</v-icon>
              </p>
            </nuxt-link>
          </div>
        </div>

        <!-- <div class="project-odd project-display">
          <div class="img-odd">Image placeholder</div>
          <div class="project-text-odd">
            <h2 class="project-title">Fearless Ticket Sellers</h2>
            <p>How do I purchase tickets for smaller, unorthodox venues?</p>
            <nuxt-link to="#">
              <p class="title project-link">
                <v-icon left>mdi-arrow-left</v-icon> See case study
              </p>
            </nuxt-link>
          </div>
        </div> -->
      </v-card-text>
    </v-card>
  </div>
</template>

<style scoped>
.portfolio-card {
  width: 85%;
  margin: auto;
}
h1 {
  letter-spacing: 4px;
}
.project-display {
  width: 100%;
  height: 250px;
  margin: 4px 0;
  border-radius: 5px;
}
.project-title {
  padding: 16px;
}

.project-even {
  text-align: left;
}
.project-odd {
  text-align: right;
}

.img-odd,
.img-even {
  height: 100%;
  width: 25%;
}
.img-even {
  float: left;
  margin-right: 16px;
  border-top-left-radius: 5px;
  border-bottom-left-radius: 5px;
}
.img-odd {
  float: right;
  margin-left: 16px;
  border-top-right-radius: 15px;
  border-bottom-right-radius: 15px;
}

a {
  text-decoration: none;
}
@media (min-width: 360px) and (max-width: 450px) {
  .v-application .display-4 {
    font-size: 2.5rem !important;
  }
}
</style>
