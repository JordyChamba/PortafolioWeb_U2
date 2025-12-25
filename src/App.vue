<template>
  <div>
    <contadorViews />
  </div>
</template>

<script>
import contadorViews from "./views/contadorView.vue";

export default {
  name: "App",
  components: {
    contadorViews,
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
