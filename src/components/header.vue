<template>
  <div class="hello">
    <div class="logo">

      <img src="../assets/vue-dc-comics-1/img/dc-logo-bg.png" alt="">
    </div>
    <nav>
      <ul>
        <li v-for="(element, index)in links" :key="index">

        </li>
      </ul>
    </nav>
    
  </div>
</template>

<script>
export default {
  name: 'Header',
  
}
data(){
  navbar:[
      
  ]
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
img{
width: 70px;
}
</style>
