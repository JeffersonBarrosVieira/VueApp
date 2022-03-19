<template>
  <div id="app">
    <HeaderApp />
    <Home msg="UbaAba" teste="lubdubi"/>
    <FooterApp />
  </div>
</template>

<script>
  import Home from './components/Home.vue';
  import HeaderApp from './components/HeaderApp.vue';
  import FooterApp from './components/FooterApp.vue';

  export default {
    name: 'App',
    components: {
      Home,
      HeaderApp,
      FooterApp,
    }
  }
</script>

<style>
  html, body {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin: 0;
    padding: 0;
  }
</style>
