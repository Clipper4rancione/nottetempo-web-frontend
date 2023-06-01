<script>
import AppJumbo from "./partials/AppJumbo.vue";
import AboutUsSection from "./partials/AboutUsSection.vue";
export default {
  name: "AppMain",

  components: {
    AppJumbo,
    AboutUsSection,
  },
};
</script>

<template>
  <main>
    <AppJumbo />
    <AboutUsSection />
  </main>
</template>



<style lang="scss" scoped>
</style>