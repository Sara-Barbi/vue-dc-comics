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
           <div class="col-8 " >
             <logoBack />
           </div>
         </div>
       </div>
     </div>
  
  </div>
</template>

<script>
import logoBack from '@/components/logoBack.vue'

export default {
  name: 'Footers',
  components:{
        logoBack
        
    }

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
  background-image: url('../assets/vue-dc-comics-1/img/footer-bg.jpg');
  background-size: cover;
  height: 450px;
  overflow: hidden;
}

@import '../assets/style/variables.scss'; 




</style>

