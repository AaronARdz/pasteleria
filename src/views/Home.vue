<template>
  <div class="home">
    <app-nav></app-nav>
    <app-header></app-header>
  </div>
</template>

<script>
// @ is an alias to /src
import Nav from "@/components/Header/Nav.vue";
import Header from "@/components/Header/Header.vue";

export default {
  name: "Home",
  components: {
    appNav : Nav,
    appHeader : Header
  }
};
</script>

<style scoped>
  .home {
    background-image: url('../assets/img/bg.png');
  }
</style>
