<template>
  <div id="About">
    <v-card class="about-card" elevation="0">
      <v-card-title>
        <h1 class="display-4 primary--text">About Me</h1>
      </v-card-title>
      <v-card-text>
        <p class="about-paragraph body-1">
          I'm a UX/UI Designer, a full-stack web developer, and JAMstacker
          living in Batesville, Arkansas.
        </p>
        <p class="about-paragraph body-1">
          Originally from Upstate New York, I moved to Batesville halfway
          through 2022 so my wife could pursue her dream job, working at a small
          liberal arts college. Prior to Arkansas, I endured seven winters in
          Minneapolis and Saint Paul, MN. During that time, I earned my
          full-stack web developer certificate through the University of
          Minnesota's College of Continuing Education. Through that program,
          I've become proficient in Javascript, jQuery, React, VueJs, Google's
          Cloud Firebase, MongoDB, and a few other technologies. My plan of
          attack on projects is to break the overall task into the smallest
          manageable pieces and build up from there.
        </p>

        <p class="about-paragraph body-1">
          It was during this program that I discovered my interest in design. It
          gave me a way to combine my artistic endeavors with my scientific
          ones.
        </p>

        <p class="about-paragraph body-1">
          When not coding, I enjoy reading and writing, watching movies, hiking,
          and travelling. One of my longshot dreams is to visit every country on
          the planet. Some of my bucket-list destinations are Japan, New
          Zealand, Portugal, South Africa, and Iceland. So far, I've been to
          Australia, the Republic of Korea, France, Canada, and Italy. As far as
          reading goes, I've recently rediscovered my love of Science Ficiton
          and fantasy, and I've always had an affinty for Marvel Comics. With
          movies, I tend to enjoy comedies over other genres. And with music,
          I'm fond of many genres, but jazz and punk rock tend to be my
          favorites.
        </p>
      </v-card-text>
    </v-card>
  </div>
</template>

<script>
export default {
  name: 'AboutPage',
}
</script>

<style scoped>
.about-card {
  width: 85%;
  margin: auto;
}
h1 {
  letter-spacing: 4px;
}
.about-paragraph {
  text-align: justify;
  text-justify: inter-word;
}
@media (min-width: 360px) and (max-width: 450px) {
  .v-application .display-4 {
    font-size: 2.5rem !important;
  }
}
</style>
