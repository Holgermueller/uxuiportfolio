<template>
  <v-app dark>
    <v-app-bar :clipped-left="clipped" app>
      <nuxt-link to="/">
        <h1>Holger Mueller</h1>
      </nuxt-link>

      <v-spacer></v-spacer>
      <div v-for="(link, i) in navArray" :key="i">
        <nuxt-link :to="link.path">
          <h3>
            <span class="mr-6">
              {{ link.linkName }}
            </span>
          </h3>
        </nuxt-link>
      </div>
    </v-app-bar>
    <v-main>
      <v-container>
        <Nuxt />
      </v-container>
    </v-main>

    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }} Holger Mueller</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'DefaultLayout',
  data: () => ({
    navArray: [
      { linkName: 'Home', path: '/' },
      { linkName: 'Portfolio', path: '/portfolio' },
      { linkName: 'About', path: '/about' },
      { linkName: 'Contact', path: '/contact' },
    ],
  }),
}
</script>

<style scoped>
h1 {
  letter-spacing: 2px;
}
a {
  font-weight: bold;
  text-decoration: none;
}
</style>
