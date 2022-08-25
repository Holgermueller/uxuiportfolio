<template>
  <div id="Contact">
    <v-img class="hero-image" src="/connect.png"></v-img>
    <ContactForm />
  </div>
</template>

<script>
import ContactForm from '../components/ContactForm.vue'
export default {
  name: 'Contact',
  components: {
    ContactForm,
  },

  head() {
    return {
      bodyAttrs: {
        class: 'reset-body',
      },
    }
  },
}
</script>

<style scoped>
.reset-body {
  margin: 0;
}
.hero-image {
  top: 0;
  left: 0;
  width: 100%;
  height: 450px;
}
</style>
