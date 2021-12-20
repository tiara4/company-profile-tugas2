<template>
  <div id="app">
    <Belajar />
  </div>
</template>

<script>
import Belajar from "./components/Belajar.vue";

export default {
  name: "App",
  components: {
    Belajar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
