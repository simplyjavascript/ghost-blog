<template>
  <section class="hero is-medium">
    <div class="hero-head">
      <div class="container"></div>
    </div>
    <div class="hero-body">
      <the-banner></the-banner>
    </div>
  </section>
</template>

<script>
import TheBanner from "@/components/Banner.vue";
export default {
  components: {
    TheBanner
  }
};
</script>

<style scoped>
section {
  font-family: "Quicksand", sans-serif;
}
</style>
