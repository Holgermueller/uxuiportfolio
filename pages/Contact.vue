<template>
  <div id="Contact">
    <!-- <v-card elevation="0">
      <v-card-title class="card-title">
        <v-img
          height="400px"
          class="hero-image white--text align-end"
          src="/connect.png"
        >
          <h1 class="border display-4">Contact</h1>
        </v-img>
      </v-card-title>
    </v-card> -->

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
