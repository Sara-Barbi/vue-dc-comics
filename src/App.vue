<template>
  <div id="app">
    <Headers />
    <Mains />
    <Footers />

    
    
  </div>
</template>

<script>

import Headers from "./components/Headers.vue"
import Mains from "./components/Mains.vue"
import Footers from "./components/Footers.vue"






export default {
  name: 'App',
  components: {
    Headers,
    Mains,
    Footers,
  }
}
</script>

<style >
@import './assets/style/global.scss';
@import './assets/style/variables.scss';




</style>
