<template>
  <div id="app">
    <NavBar msg="welcome to your vue.js app"/>
    <JumbotronSection/>
    <CTA/>
  </div>
</template>

<script>
import NavBar from './components/NavBar_1.vue';
import JumbotronSection from './components/JumbotronSection.vue';
import CTA from './components/CTA.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    JumbotronSection,
    CTA,
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
