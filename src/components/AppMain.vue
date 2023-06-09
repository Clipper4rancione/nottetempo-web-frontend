<script>
import AppJumbo from "./partials/AppJumbo.vue";
import AboutUsSection from "./partials/AboutUsSection.vue";
import TheFoundersSection from "./partials/TheFoundersSection.vue";
export default {
  name: "AppMain",

  components: {
    AppJumbo,
    AboutUsSection,
    TheFoundersSection,
  },
};
</script>

<template>
  <main>
    <AppJumbo />
    <AboutUsSection />
    <TheFoundersSection />
  </main>
</template>



<style lang="scss" scoped>
</style>