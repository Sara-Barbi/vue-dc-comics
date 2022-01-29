<template>
  <div class="hello">
    <div class="container-fluid acontain">

      <div class="container containeraz ">
        <div class="row align-content-center">
          <div class="col-12  linehei">
            <h4> -->Content goes Here </h4>
          </div>
        </div>
      </div>

    </div>
    <div class="container-fluid bcontain">
      <div class="container">
        <div class="row">
        
           <padreLogos/>
         
        </div>
      </div>
    </div>

    
  </div>
</template>

<script scope>
import padreLogos from './slider/padreLogos.vue';

export default {
  name: 'Mains',
  components: {
    padreLogos
  }
}






</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang = "scss" scoped>
@import '../assets/style/variables.scss';

.acontain{
background-color: black;
color: white;


}
.containeraz{
  display: flex;
  align-content: center;
  min-height: 150px;
}
ul{
  display: flex;
  align-content: center;
  margin: auto 0;
  
   li {
    display: inline-block;
    margin: 0 10px;
    
    span, img {
      color: #fcfcfc;
        text-decoration: none;
        padding: 20px ;
        font-family: 'Lucida Sans Unicode';
        font-weight: 600;

    }
  }
}


.bcontain{
  background-color: rgb(44, 188, 193);
  
}


@import '../assets/style/variables.scss' ;

</style>
