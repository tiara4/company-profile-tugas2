<template>
  <div id="app">
    <Latihan />
  </div>
</template>

<script>
import Latihan from "./components/Latihan.vue";

export default {
  name: "App",
  components: {
    Latihan,
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
