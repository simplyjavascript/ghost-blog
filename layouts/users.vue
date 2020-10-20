<template>
  <div>
    <section class="hero is-medium">
      <div class="hero-head">
        <div class="container">
          <the-header></the-header>
        </div>
      </div>
    </section>
    <Nuxt />
  </div>
</template>
<script>
import TheHeader from "@/components/Header.vue";
export default {
  components: {
    TheHeader
  }
};
</script>
