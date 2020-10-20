<template>
  <!-- This is a nested route -->
  <div>
    <nuxt-child />
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Primary title
          </h1>
          <h2 class="subtitle">
            Primary subtitle
          </h2>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  layout: "users"
};
</script>
