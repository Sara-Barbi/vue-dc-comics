<template>

<div class="hello">
  <div class="container-small d-flex align-content-center my-line-height">

    <div class="logo">
      <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
    </div>
    <nav>
      <ul class="">
          <li v-for="(element, index) in links" :key="index">
            <a href="#" :class="{'active': element.current}">{{element.text}}</a>
          </li>
      </ul>
    </nav>
  
  </div>
</div>
</template>

<script>
export default {
name: 'Headers',


data() {
return{
links:[
  { text: "Home",
    url: "#",
    current:"false",
  },
      
  { text: "Contattaci",
    url: "#",
    current:"false",
  },

  { text: "Cosa Offriamo",
    url: "#",
    current:"false",
  },

  { text: "I nostri prodotti",
    url: "#",
    current:"false",
  },

  { text: "Home",
    url: "#",
    current:"false",
  },
]
}
}
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang = "scss" scoped >
.container-small{
max-width: 1100px;
margin: 0 auto;
}
.my-line-height{
line-height: 70px;
justify-content: space-between;
}
h3 {
margin: 40px 0 0;
}
ul {
list-style-type: none;
padding: 0;
  li {
      display: inline-block;
      margin: 0 10px;
      a {
          color: #42b983;
        } 
    }
}

img{
width: 70px;
}


@import '../assets/style/variables.scss' 

</style>












