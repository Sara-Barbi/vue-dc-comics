<template>
  <div class="hello">
    <div class="container-fluid">

      <div class="container">
        <h4> -->Content goes Here </h4>
      </div>

    </div>
    <div class="container-fluid">
      <div class="container">
         <ul>
           <li v-for="(element, index) in aboutUs" :key="index" >
             <img :src="aboutUs[index].stemma" >
             <span>{{aboutUs[index].descrizione}}</span>
           </li>
         </ul>
      </div>
    </div>

    <h1>MAIN</h1>
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
<style>
@import '../assets/style/variables.scss' 

</style>
