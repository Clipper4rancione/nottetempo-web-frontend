<script>
import StreamerCard from "./StreamerCard.vue";
export default {
  name: "TheFounderSection",
  components: {
    StreamerCard,
  },
};
</script>

<template>
  <section class="founder_section">
    <div class="container">
      <h2 class="text-center py-5">LA NOSTRA STREAMCOMP</h2>
      <div class="row d-flex justify-content-center">
        <div class="col-6">
          <StreamerCard />
        </div>
        <div class="col-6">
          <StreamerCard />
        </div>
        <div class="col-6">
          <StreamerCard />
        </div>
        <div class="col-6">
          <StreamerCard />
        </div>
        <div class="col-6 py-3">
          <StreamerCard />
        </div>
      </div>
    </div>
  </section>
</template>



<style lang="scss" scoped>
.founder_section {
  background: rgb(25, 25, 25);
  background: linear-gradient(
    180deg,
    rgba(25, 25, 25, 1) 46%,
    rgba(42, 42, 42, 1) 86%
  );
}
</style>