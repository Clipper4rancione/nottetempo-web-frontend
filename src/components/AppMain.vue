<script>
import AppJumbo from "./partials/AppJumbo.vue";
import AboutUsSection from "./partials/AboutUsSection.vue";
import TheFoundersSection from "./partials/TheFoundersSection.vue";
import ContacUsSection from "./partials/ContactUsSection.vue";
export default {
  name: "AppMain",

  components: {
    AppJumbo,
    AboutUsSection,
    TheFoundersSection,
    ContacUsSection,
  },
};
</script>

<template>
  <main id="main_sec">
    <AppJumbo />
    <AboutUsSection />
    <TheFoundersSection />
    <ContacUsSection />
  </main>
</template>



<style lang="scss" scoped>

</style>