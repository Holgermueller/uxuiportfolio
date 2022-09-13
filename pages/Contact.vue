<template>
  <div id="Contact">
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
