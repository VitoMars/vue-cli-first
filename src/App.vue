<template>
   <div id="app">
      <titolo msg="QUACK" />

      <img src="./assets/img/duck.jpg" alt="" />
   </div>
</template>

<script>
import titolo from "./components/Quack.vue";

export default {
   name: "App",
   components: {
      titolo,
   },
};
</script>

<style lang="scss">
#app {
   font-family: Avenir, Helvetica, Arial, sans-serif;
   -webkit-font-smoothing: antialiased;
   -moz-osx-font-smoothing: grayscale;
   text-align: center;
   color: #2c3e50;
   margin-top: 60px;
}
</style>
