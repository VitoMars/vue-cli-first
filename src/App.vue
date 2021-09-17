<template>
   <div id="app">
      <titolo msg="La mia prima app con Vue CLI!" />
      <quack msg="quack" />
   </div>
</template>

<script>
import titolo from "./components/Titolo.vue";
import quack from "./components/Hero.vue";

export default {
   name: "App",
   components: {
      titolo,
      quack,
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
