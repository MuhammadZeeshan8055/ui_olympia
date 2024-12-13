<template>
  <div>
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Header from "~/components/Header.vue";
import Footer from "~/components/Footer.vue";

export default {
  name: "DefaultLayout", // Use a descriptive name for the layout
  components: {
    Footer,
    Header
  }
};
</script>
