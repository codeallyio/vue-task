<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Launches />
</template>

<script>
import Launches from "./components/Launches";

export default {
  name: "App",
  components: {
    Launches,
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
  margin-top: 60px;
}
</style>

<style scoped>
img {
  width: 120px;
}
</style>