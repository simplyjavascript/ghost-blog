<template>
  <nav class="navbar">
    <div class="navbar-menu">
      <div class="navbar-start">
        <nuxt-link class="navbar-item" to="/"> Home </nuxt-link>
        <nuxt-link class="navbar-item" to="/users"> Users </nuxt-link>
        <nuxt-link class="navbar-item" to="/users/2"> Second User </nuxt-link>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <the-social></the-social>
        </div>
      </div>
    </div>
  </nav>
</template>
<script>
import TheSocial from "./Social.vue";
export default {
  components: {
    TheSocial
  }
};
</script>
