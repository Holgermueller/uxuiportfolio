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
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
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
@media (min-width: 360px) and (max-width: 450px) {
  .v-application .display-4 {
    font-size: 2.5rem !important;
  }
}
</style>
