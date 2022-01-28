<template>
  <div class="hello">
     <div class="container-fluid elback">
       <div class="container">
         <div class="row">
           <div class="col-1">
              <h4>DC COMICS</h4>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>
              <h4>SHOP</h4>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>
           </div>
           <div class="col-1">
              <h4>DC </h4>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>

           </div>
           <div class="col-1">
              <h4>SITES</h4>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>

           </div>
         </div>
       </div>
     </div>
  
  </div>
</template>

<script>
export default {
  name: 'Footers',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang = "scss" scoped>

h4{
  color: white;
      }
ul{
   color: rgb(99, 97, 100);
   list-style-type: none;
}
.elback{
   background-image: src '../assets/style/vue-dc-comics-1/footer-bg.png';
}

@import '../assets/style/variables.scss' 




</style>

