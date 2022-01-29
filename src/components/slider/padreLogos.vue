<template>
  <div class=" d-flex">
      
    <figlioLogos 
    v-for ="(slide, index) in slides" :key="index"
    :prodotto="slide" />
  
  </div>
</template>

<script>
import figlioLogos from './figlioLogos.vue';


export default {

  name:'padreLogos',

  components :{
     figlioLogos
  },
  data(){
      return{
        slides:[
                     
        {
          image:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          text: "DIGITAL COMICS"
        },

        {
          image:"../assets/vue-dc-comics-1/img/buy-comics-merchandise.png",
          text: "DC MERCHANDISE"
        },  

        {
          image:"../assets/vue-dc-comics-1/img/buy-comics-subscriptions.png",
          text: "SUBSCRIPTION"
        },
         
        {
          image:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          text: "DC POWER VISA"
        }
        ,
        {
          image:"../assets/vue-dc-comics-1/img/buy-comics-digital-comics.png",
          text: "DIGITAL COMICS"
        }
             
             
             
          ]
      }
  }

}
</script>

<style scoped lang="scss">


</style>