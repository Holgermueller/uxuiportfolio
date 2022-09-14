<template>
  <div id="Portfolio">
    <v-hover v-slot="{ hover }">
      <v-card>
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out primary darken-2 v-card--reveal text-h2 white--text"
            style="height: 100%"
          >
            Demo transition
          </div>
        </v-expand-transition>
        <v-card-text>
          <h1>Demo Card</h1>
        </v-card-text>
      </v-card>
      <!-- <v-card class="portfolio-card" elevation="0">
        <v-expand-x-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out primary"
            style="height: 100%"
          >
            <v-card-title>
              <v-img class="img-even" src="./fts.png">
                <h1 class="display-4 primary--text">Portfolio</h1></v-img
              >
            </v-card-title>
            <v-card-text>
              <div class="project-display">
                <div class="project-text-even">
                  <h2 class="project-title">Fearless Ticket Sellers</h2>
                  <p>
                    How do I purchase tickets for smaller, unorthodox venues?
                  </p>
                  <nuxt-link to="/FTSCaseStudy">
                    <p class="title project-link">
                      See case study <v-icon right>mdi-arrow-right</v-icon>
                    </p>
                  </nuxt-link>
                </div>
              </div>
            </v-card-text>
          </div>
        </v-expand-x-transition>
      </v-card> -->
    </v-hover>
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

.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  opacity: 0.5;
  position: absolute;
  width: 100%;
}

.project-title {
  padding: 16px;
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
