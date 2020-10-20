<template>
  <div class="container has-text-centered">
    <img :src="imageLink" width="150" height="40" />
    <h2 class="subtitle">{{ bannerText }}</h2>
  </div>
</template>
<script>
export default {
  data() {
    return {
      imageLink: "https://cdn.emk.dev/templates/bulma-logo-light.png",
      bannerText: "Ghost's Casper theme made with Bulma"
    };
  }
};
</script>
