<template>
  <div>
    <main-nav />
    <router-view />
  </div>
</template>

<script>
import NavBar from "./components/NavBar";

export default {
  components: {
    "main-nav": NavBar,
  },
};
</script>

<style></style>
