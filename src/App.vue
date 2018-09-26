<template>
  <div id="app">
    <caculate />
  </div>
</template>

<script>
import caculate from "./view/caculate.vue";

export default {
  name: "app",
  components: {
    caculate
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
caculate {
  border: 1px solid A2A2A2
}
</style>
