<template>
  <div class="main pa-4" id="app">

      
      
      <v-card elevation="15" class="pa-5 text-center">
        <v-img src="https://picsum.photos/id/11/500/300">
          
        </v-img> 
        <h2 class="pa-3 display-1 font">রাসেল আহমেদ</h2>
        <v-btn class="ma-2" dark color="#D32F2F">
          <v-icon dark>
            mdi-youtube
          </v-icon>
          
        </v-btn>
        <v-btn class="ma-2" dark color="indigo">
          <v-icon dark>
            mdi-facebook
          </v-icon>
          
        </v-btn>
        <v-btn class="ma-2" dark color="#424242">
          <v-icon dark>
            mdi-github
          </v-icon>
          
        </v-btn>
      </v-card>
      
      
      

  </div>
  

  


  
</template>

<style type="text/css" media="all">

@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');

html, body {
  font-family: 'Roboto', sans-serif !important! ;
 
}

#app {
  font-family: 'Roboto', sans-serif !important;
}
  .header{
    min-height: 100vh;
    background-color: coral;
    background-position: center;
    
  }
  nav{
    background: black;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 10px 20px;
    position: fixed;
    width: 100%;
    z-index: 1000;
    
    
    
  }
  nav .nav-links{
    flex:1;
    text-align: right;
  }
   ul{
  list-style: none;
  
  }
   ul li{
    list-style-type: none;
    display: inline-block; 
  }
  ul li a{
    text-decoration: none;
    padding: .5rem;
    display: block;
    color: white !important;
    font-weight: bold;
    transition: .4S;
  }
  ul li a:hover{
    background: #555 !important;
    border-radius: 4px;
    
    
  }
  .content-box{
    padding: 150px 100px 0px 100px;
  }
  
  .my-row{
    display: flex;
    margin-top: 50px;
    justify-content: space-between;
    flex-direction: column;
  }
  .service-col{
    flex-basis: 100%;
    box-shadow: 0 0 20px 0 rgba(0,0,0,.1);
    margin: auto;
    padding: 20px 10px;
    margin-bottom: 5%;
    position: relative;
    transition: transform .5s;
    border-radius: 5px;
    
  }
  .service-col h2{
    margin-bottom: 5px;
    text-align: center;
  }
  .service-col:hover{
    transform: translateY(-4px);
  }
</style>
