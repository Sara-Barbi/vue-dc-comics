<template>
  <div class="hello">
     <div class="container-fluid elback">
       <div class="container">
         <div class="row">
           <div class="col-2 text-center mt-5">
              <h5>DC COMICS</h5>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>
              <h5>SHOP</h5>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>
           </div>
           <div class="col-2 text-center mt-5">
              <h5>DC </h5>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>

           </div>
           <div class="col-2 text-center mt-5">
              <h5>SITES</h5>
              <ul>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
                <li>Lorem</li>
              </ul>

           </div>
           <div class="col-6 " >
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
@import '../assets/style/variables.scss';

h5{
  color: white;
      }
ul{
   color: rgb(99, 97, 100);
   font-size: 10px;
   list-style-type: none;
   padding-left: 0px;
}
.elback{
  background-image: url('../assets/vue-dc-comics-1/img/footer-bg.jpg');
  background-size: cover;
  height: 450px;
  overflow: hidden;
}

@import '../assets/style/variables.scss'; 




</style>

