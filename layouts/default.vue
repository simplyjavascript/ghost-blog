<template>
  <div>
    <!-- Please load different pages here in this placeholder -->
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
import TheHeader from "@/components/Header";
export default {
  components: {
    TheHeader
  }
};
</script>
