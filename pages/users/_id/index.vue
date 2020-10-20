<template>
  <section class="hero is-medium">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h2 class="subtitle">Single user with ID {{ $route.params.id }}</h2>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  // special method NUXT executes before rendering the route.
  validate(data) {
    return /^\d+$/.test(data.params.id);
  },
  layout: "users"
};
</script>
