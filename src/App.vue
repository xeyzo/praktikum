<template>
  <div id="app" class="relative min-h-screen">
    <div id="nav">
      <nav-bar />
    </div>
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
<style>

