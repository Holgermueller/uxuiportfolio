<template>
  <div id="Portfolio">
    <v-card class="portfolio-card" elevation="0">
      <v-card-title><h1 class="display-4">Portfolio</h1></v-card-title>

      <v-card-text>
        <div class="project-even project-display">
          <div class="img-even">Image placeholder</div>
          <h2 class="project-title">Fearless Ticket Sellers</h2>
        </div>

        <div class="project-odd project-display">
          <div class="img-odd">Image placeholder</div>
          <h2 class="project-title">Fearless Ticket Sellers</h2>
        </div>
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
  background-color: aqua;
  margin: 4px 0;
  border-radius: 15px;
}

.project-even {
  text-align: right;
}
.project-odd {
  text-align: left;
}

.img-odd,
.img-even {
  background-color: black;
  height: 100%;
  width: 25%;
}
.img-even {
  float: left;
  border-top-left-radius: 15px;
  border-bottom-left-radius: 15px;
}
.img-odd {
  float: right;
  border-top-right-radius: 15px;
  border-bottom-right-radius: 15px;
}
.project-title {
  padding: 8px;
}
</style>
