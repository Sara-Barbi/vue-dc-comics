<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <header />
    <main />
    <footer />
  </div>
</template>

<script>
import header from './components/header.vue';
import main from './components/main.vue';
import footer from './components/footer.vue';


export default {
  name: 'App',
  components: {
    header,
    main,
    footer,
  }
}
</script>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
