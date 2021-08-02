<template>
     <VueScrollFixedNavbar>
    <nav class="sticky-top">
         <div class="menu-item"><a href="#">Disney+Hotstar</a></div>
         <Dropdown  title="TV" :items="tv" id="sublist"/>
         <Dropdown title="Movies" :items="movies" id="sublist"/>
         <Dropdown title="Sports" :items="sports" id="sublist"/>
        <div class="menu-item" id="sublist"><a href="#">Premium</a></div>
        <div class="menu-item" id="sublist"><a href="#">Disney+New</a></div>
        <div class="menu-item kid" id="sublist"><a href="#"><i :style="{color:'orange'}">Kids</i></a></div>
         <form>
            <div class="form text-white  border-bottom srh" id="srch">Search<span class="sico text-white"> &#128269;</span></div></form>

        <div class="sub" id="list"><button class="bg-primary rounded"><router-link to="Subscribe" class="text-white text-decoration-none fs-6">Subscribe</router-link></button></div>
        <div class="log" id="listlog"><router-link to="#" class="text-white text-decoration-none">Login</router-link></div>
       
    </nav>
    </VueScrollFixedNavbar>
</template>

<script>

import Dropdown from './Dropdown.vue'
export default {
  name: 'navbar',
  components: {
    Dropdown,
  },
  data() {
    return{
      tv: [ 
            {
             title:'Vijay super',
             link:"#"
             },
             {
             title:'Hotstar Special',
             link:"#"
             },
             {
             title:'Quix',
             link:"#"
             },
              {
             title:'Star Jalsha',
             link:"#"
             },
               {
             title:'StarPlus',
             link:"#"
             },
               {
             title:'Star Bharat',
             link:"#"
             },
               {
             title:'Star sports',
             link:"#"
             },
               {
             title:'Star Jalsha',
             link:"#"
             }
            ],
           
             movies: [ 
            {
             title:'Tamil',
             link:"#"
             },
             {
             title:'Telugu',
             link:"#"
             },
             {
             title:'Malayalam',
             link:"#"
             },
             {
             title:'Hindi',
             link:"#"
             },
              {
             title:'English',
             link:"#"
             },
               {
             title:'Marathi',
             link:"#"
             }

            ],
              sports: [ 
            {
             title:'Hockey',
             link:"#"
             },
             {
             title:'Cricket',
             link:"#"
             },
             {
             title:'Tennis',
             link:"#"
             },
             {
             title:'Volley Ball',
             link:"#"
             },
              {
             title:'FootBall',
             link:"#"
             },
              {
             title:'Golf',
             link:"#"
             }
              ]
    }
  },
}
</script>
<style>

nav{
    display: flex;
    align-items:center;
     width:100%;
}
nav .menu-item{
    color:white;
    padding:15px 20px;
    position:relative;
    display: flex;
}
nav .menu-item a{
    color:white;
    text-decoration: none;
    
}
div .srh{
  margin-left:60px;
  
}
.form {
  border-bottom: 1px solid white;
}
.sico {
  margin-left: 100px;
}
div .sub{
 margin-left:35px;
}
.log{ 
  margin-left: 20px;
}
@media (max-width:280px) {
  #sublist{
    display: none;
  }
  #srch{
    display: none;
  }
  .sub{
    float:right;
  }
  #listlog{
    display: none;
  }
}
@media (min-width:300px) and (max-width:400px) {
  #sublist{
    display: none;
  }
  #srch{
    display: none;
  }
  .sub{
    float:right;
  }
}
 @media (min-width:401px) and (max-width:445px) {
  #sublist{
    display: none;
  }
   #list{
    display: none;
  }
  #listlog{
    display: none;
  }
}
 @media (min-width:446px) and (max-width:644px) {
  #sublist{
    display: none;
  }
   #list{
    display: none;
  }
 
}
 @media (min-width:645px) and (max-width:900px) {
  #sublist{
    display: none;
  }
   #srch{
     margin-left: 150px;
   }
 
}
@media (min-width:901px) and (max-width:1200px) {
  
   #srch{
     display: none;
   }
   #list{
    display: none;
  }
  #listlog{
    display: none;
  }
 
}

 
</style>



