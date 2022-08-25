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
    <div class="case-study-header">
      <v-img
        class="full"
        height="1000px"
        width="500px"
        src="./ftsfull.png"
      ></v-img>
    </div>

    <v-img
      class="full"
      height="1000px"
      width="500px"
      src="./hifipay.png"
    ></v-img>
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
.case-study-header {
  height: 1000px;
}
.full.resize {
  float: left;
  margin-right: 16px;
  display: block;
  max-height: 1000px;
  max-width: 700px;
  height: auto;
  width: auto;
}
.app-name {
  float: right;
}
</style>
