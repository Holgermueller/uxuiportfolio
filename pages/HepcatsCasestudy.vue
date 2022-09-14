<template>
  <div id="HepcatsCaseStudy">
    <nuxt-link to="/Portfolio">
      <v-chip outlined>
        <v-icon left>mdi-arrow-left</v-icon>
        Back
      </v-chip>
    </nuxt-link>
    <h1 class="app-name display-4">Hepcats</h1>
    <h2 class="display-2">Where the cool kids get their clothes</h2>
  </div>
</template>

<script>
export default {
  name: 'HepcatsPage',
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
</style>
