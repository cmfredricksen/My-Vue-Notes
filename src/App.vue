<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <Header msg="You are getting this!" />
  <HowToVue />
  <ExploreVue />
  <AboutApp />
  <MakeComponent />
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
// import Header from "./components/Header.vue";
import HowToVue from "./components/HowToVue";
import ExploreVue from "./components/ExploreVue";
import AboutApp from "./components/AboutApp";
import MakeComponent from "./components//MakeComponent";

export default {
  name: "App",
  components: {
    // HelloWorld,
    // Header,
    HowToVue,
    ExploreVue,
    AboutApp,
    MakeComponent,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
