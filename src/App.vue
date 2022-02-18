<template>
  <div id="app">
    <HeroImg></HeroImg>
    <TitleVue></TitleVue>
  </div>
</template>

<script>
  import TitleVue from "./components/Title.vue";
  import HeroImg from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    TitleVue,
    HeroImg
  }
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
