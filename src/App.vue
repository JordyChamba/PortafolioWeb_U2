<template>
  <div>
    <!--contadorView />-->
    <!--DirectivasView />-->
    <PreguntaView />
  </div>
</template>

<script>
import contadorViews from "./views/contadorView.vue";
import DirectivasView from "./views/DirectivasView.vue";
import PreguntaView from "./views/PreguntaView.vue";

export default {
  name: "App",
  components: {
    contadorViews,
    DirectivasView,
    PreguntaView,
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
