<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <MainTitle />
    <JumboTron />
  </div>
</template>

<script>
import MainTitle from "./components/MainTitle.vue";
import JumboTron from "./components/JumboTron.vue";

export default {
  name: "App",
  components: {
    MainTitle,
    JumboTron,
  },
};
</script>

<style lang="scss">
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
