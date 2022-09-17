<template>
  <div id="Home">
    <v-card class="home-card" elevation="0">
      <v-card-title class="headline">
        <h1 class="display-4 primary--text first">Holger</h1>
        <h1 class="display-4 last">Mueller</h1>
      </v-card-title>
      <v-card-subtitle>
        <br />
        <hr class="my-3" />
        <br />
        <h2 class="headline textLight--text">
          UX/UI Designer | Front-End Developer | JAMstacker
        </h2>
      </v-card-subtitle>
      <v-card-text>
        <h3 class="body-1 textLight--text">
          Hello, I'm Holger Mueller, a UX designer and developer living in
          Batesville, AR. I believe technology and art can come together to make
          the world a better place. I'm currently exploring new employment
          opportunities!
        </h3>
      </v-card-text>
    </v-card>

    <div class="socials">
      <div class="link" v-for="(link, i) in links" :key="i">
        <a :href="link.link" target="_blank">
          <v-icon x-large>{{ link.icon }} </v-icon>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',

  data: () => ({
    links: [
      {
        link: 'https://github.com/Holgermueller',
        icon: 'mdi mdi-github',
      },
      {
        link: 'https://stackoverflow.com/users/9111512/holger-mueller?tab=profile',
        icon: 'mdi mdi-stack-overflow',
      },
      {
        link: 'https://www.linkedin.com/in/holger-mueller-75855114a/',
        icon: 'mdi mdi-linkedin',
      },
      {
        link: 'https://holgermueller.github.io/Resume/',
        icon: 'mdi mdi-file',
      },
      {
        link: 'mailto:9jholger@gmail.com',
        icon: 'mdi mdi-email',
      },
    ],
  }),
}
</script>

<style scoped>
.home-card {
  width: 85%;
  margin: auto;
}
h1 {
  letter-spacing: 4px;
}
.socials {
  width: 55%;
  margin: 2rem auto;
  border-radius: 5px;
  display: flex;
  justify-content: space-between;
  column-gap: 0.5rem;
  flex-wrap: wrap;
}
a {
  text-decoration: none;
}
.link,
.v-icon {
  border-radius: 5px;
}
.v-icon:hover,
.link:hover {
  background-color: #13a7be;
  color: white;
}

@media (min-width: 360px) and (max-width: 450px) {
  .v-application .display-4 {
    font-size: 2.5rem !important;
  }
}
</style>
