<template>
  <div id="app">
    <app-header></app-header>
    <!--<router-view/>-->
    <app-container></app-container>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import header from "./components/Header.vue"
  import container from "./components/Container.vue"
  import footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    appHeader : header,
    appContainer : container,
    appFooter : footer,
  }
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
