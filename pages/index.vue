<template>
  <div id="Home">
    <v-card class="home-card" elevation="0">
      <v-card-title class="headline">
        <h1 class="display-4 first">Holger</h1>
        <h1 class="display-4 last">Mueller</h1>
      </v-card-title>
      <v-card-subtitle>
        <br />
        <hr class="my-3" />
        <br />
        <h2 class="display-1">UX/UI Designer | Front End Developer</h2>
      </v-card-subtitle>
      <v-card-text>
        <h3 class="body-1">
          Hello, I'm Holger Mueller, a UX designer and developer living in
          Batesville, AR. He is currently exploring new employment
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
</style>
