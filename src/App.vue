<template>
  <div id="app" class="relative min-h-screen">
      <nav-bar />
    <router-view />
  </div>
</template>

<script>
import NavBar from "@/components/Navbar/Navbar.vue";

export default {
  name: "App",
  components: {
    NavBar
  }
};
</script>

