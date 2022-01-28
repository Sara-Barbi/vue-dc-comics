<template>

<div class="hello">
  <div class="container-small d-flex align-content-center my-line-height">

    <div class="logo">
      <img src="../assets/vue-dc-comics-1/img/dc-logo.png" alt="">
    </div>
    <nav>
      <ul class="">
          <li v-for="(element, index) in links" :key="index" @click="element.current" >
            <a href="#" :class="{active : element.current}">{{element.text}}</a>
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
    current: true,
  },
      
  { text: "Contattaci",
    url: "#",
    current: false,
  },

  { text: "Cosa Offriamo",
    url: "#",
    current: false,
  },

  { text: "I nostri prodotti",
    url: "#",
    current: false,
  },

  { text: "Home",
    url: "#",
    current: false,
  },
]
}
}
}
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->

<style lang = "scss" scoped >

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
      display: $line;
      margin: 0 10px;
      

      a {
          color: #000000;
          text-decoration: none;
          padding: 25px  10px;
          font-family: 'Lucida Sans Unicode','Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande',  Geneva, Verdana, sans-serif ;
          font-weight: 800;

          &.active{
                  color: rgb(32, 105, 178);
                  border-bottom:rgb(32, 105, 178);
                  padding: 40px,20px;
                  border-bottom: 5px solid rgb(32, 105, 178);;
                  }

        } 
    }
}

img{
width: 70px;
}


@import '../assets/style/variables.scss' ;

</style>












