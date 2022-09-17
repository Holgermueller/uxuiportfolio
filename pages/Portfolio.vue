<template>
  <div id="Portfolio">
    <v-card class="portfolio-card" elevation="0">
      <v-card-title>
        <h1 class="display-4 primary--text">Portfolio</h1>
      </v-card-title>
    </v-card>

    <v-container class="portfolio" fluid>
      <v-layout row wrap>
        <v-flex
          xs12
          sm12
          md6
          lg6
          xl6
          v-for="(project, index) in projects"
          :key="index"
        >
          <v-hover v-slot="{ hover }">
            <v-card class="project-card">
              <v-expand-transition>
                <div
                  v-if="hover"
                  class="d-flex transition-fast-in-fast-out darken-2 v-card--reveal white--text"
                  style="height: 100%"
                >
                  <div class="display-1 project-link text--white">
                    <nuxt-link :to="project.link">
                      See the case study <v-icon right>mdi-arrow-right</v-icon>
                    </nuxt-link>
                  </div>
                </div>
              </v-expand-transition>
              <v-card-title>
                <h2>
                  {{ project.title }}
                </h2>
              </v-card-title>
              <v-card-text>
                <p>{{ project.descrip }}</p>
              </v-card-text>
            </v-card>
          </v-hover>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
export default {
  name: 'PortfolioPage',

  data: () => ({
    projects: [
      {
        title: 'Jobz',
        link: '/JobzCasestudy',
        descrip:
          'A mobile app and responsive website to help first-generation immigrants find jobs',
      },
      {
        title: 'HepCatz',
        link: '/HepcatsCasestudy',
        descrip: 'A responsive e-commerce site.',
      },
      {
        title: 'Fearless Ticket Sellers',
        link: '/FTSCaseStudy',
        descrip:
          'A mobile app that allows underground bands sell tickets to untraditional venues.',
      },
    ],
  }),
}
</script>

<style scoped>
.portfolio-card {
  width: 85%;
  margin: auto;
}
h1 {
  letter-spacing: 4px;
}

.project-card {
  margin: 8px;
}

.v-card--reveal {
  align-items: center;
  bottom: 0;
  justify-content: center;
  background: rgba(19, 167, 190, 0.5);
  position: absolute;
  width: 100%;
}

.project-title {
  padding: 16px;
}
.v-icon {
  color: white;
}
a {
  text-decoration: none;
  color: white;
}
@media (min-width: 360px) and (max-width: 450px) {
  .v-application .display-4 {
    font-size: 2.5rem !important;
  }
}
</style>
