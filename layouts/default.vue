<template>
  <v-app dark>
    <v-app-bar class="header" elevation="0" app>
      <nuxt-link to="/">
        <h1 class="display-1 primary--text">HM</h1>
      </nuxt-link>

      <v-spacer></v-spacer>
      <div v-for="(link, i) in navArray" :key="i">
        <nuxt-link :to="link.path">
          <h3 class="subtitle-1 primary--text">
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
        >Copyright &copy; 2022 - {{ new Date().getFullYear() }} Holger Mueller |
        Built with Nuxtjs</span
      ><v-spacer></v-spacer>
      <span class="socials">
        <a href="https://github.com/Holgermueller">
          <v-icon>mdi-github</v-icon></a
        >
        <a href="https://www.linkedin.com/in/holger-mueller-75855114a/">
          <v-icon>mdi-linkedin</v-icon></a
        >
        <a
          href="https://stackoverflow.com/users/9111512/holger-mueller?tab=profile"
        >
          <v-icon>mdi-stack-overflow</v-icon></a
        >
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
      { linkName: 'Resume', path: '/resume' },
    ],
  }),
}
</script>

<style scoped>
.theme--light.v-app-bar.v-toolbar.v-sheet {
  background-color: #f8f8ff;
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
  background-color: #f8f8ff;
}
</style>
