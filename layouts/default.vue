<template>
  <v-app dark>
    <v-app-bar class="header" elevation="0" app>
      <nuxt-link to="/">
        <h1 class="display-1">Holger Mueller</h1>
      </nuxt-link>

      <v-spacer></v-spacer>
      <div v-for="(link, i) in navArray" :key="i">
        <nuxt-link :to="link.path">
          <h3 class="subtitle-1">
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

    <v-footer app>
      <span
        >&copy; {{ new Date().getFullYear() }} Holger Mueller | Built with
        Nuxtjs</span
      ><v-spacer></v-spacer>
      <span class="socials">
        <nuxt-link to="https://github.com/Holgermueller">
          <v-icon>mdi-github</v-icon>
        </nuxt-link>
        <nuxt-link to="https://www.linkedin.com/in/holger-mueller-75855114a/">
          <v-icon>mdi-linkedin</v-icon>
        </nuxt-link>
        <nuxt-link
          to="https://stackoverflow.com/users/9111512/holger-mueller?tab=profile"
        >
          <v-icon>mdi-stack-overflow</v-icon>
        </nuxt-link>
      </span>
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
/* .container {
  padding: 0;
} */
.header {
  background: transparent;
}
h1 {
  letter-spacing: 2px;
}
a {
  font-weight: bold;
  text-decoration: none;
}
footer {
  position: absolute;
  left: 0;
  bottom: 0;
  background-color: inherit;
}
</style>
