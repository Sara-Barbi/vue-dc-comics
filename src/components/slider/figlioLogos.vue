<template>
<div>
    <ul >
        <li >
           <img :src="prodotto.image" >
           <span>{{prodotto.text}}</span>
        </li>
    </ul>
</div>
</template>

<script>


export default {
name: 'figlioLogos',
props:{
      prodotto: Object,

  },

}
</script>

<style lang="scss" scoped>
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
        font-size: 10px;
        font-family: 'Lucida Sans Unicode';
        font-weight: 600;

    }
  }
}


















</style>