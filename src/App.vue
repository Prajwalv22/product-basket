<template>
  <div id="app">
    <!-- <navHeader /> -->
    <MainView />
  </div>
</template>

<script>
// import navHeader from './components/navHeader.vue';
import MainView from "./components/MainView.vue";

export default {
  name: 'App',
  components: {
    MainView,
  }
}
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
