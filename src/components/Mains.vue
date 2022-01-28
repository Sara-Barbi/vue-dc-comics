<template>
  <div class="hello">
    <div class="container-fluid acontain">

      <div class="container  ">
        <div class="row ">
          <div class="col-12  linehei">
            <h4> -->Content goes Here </h4>
          </div>
        </div>
      </div>

    </div>
    <div class="container-fluid bcontain">
      <div class="container containeraz">
        <div class="row">
         <ul>
           <li v-for="(element, index) in aboutUs" :key="index" >
             <img :src="aboutUs[index].stemma" >
             <span>{{aboutUs[index].descrizione}}</span>
           </li>
         </ul>
        </div>
      </div>
    </div>

    
  </div>
</template>

<script scope>
export default {
  name: 'Mains',
  data(){
    return{
      aboutUs:[
        
        {
          stemma:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          descrizione: "DIGITAL COMICS"
        },

        {
          stemma:"../assets/vue-dc-comics-1/img/buy-comics-merchandise.png",
          descrizione: "DC MERCHANDISE"
        },  

        {
          stemma:"../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png",
          descrizione: "SUBSCRIPTION"
        },
         
        {
          stemma:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          descrizione: "DC POWER VISA"
        }
        ,
        {
          stemma:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          descrizione: "DIGITAL COMICS"
        }
      ]
    }
  }
}



</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang = "scss" scoped>
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
