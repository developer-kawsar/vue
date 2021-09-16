<template>
 
    
<!---
 <v-app>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
  ---->
  <div class="main">
    <nav class="navigation">
      <div class="logo">
        <h4>Skybd</h4>
      </div>
      <div class="menu">
        <div>
          {{age}}
        </div>
        <ul>
          <li v-for="num in 100" :key="num.id">{{num}}</li>
          <li>{{gf}}</li>
          
        </ul>
      </div>
      
    </nav>
  </div>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
    gf:"tamanna",
    age:16
  }),
  mounted(){
    setInterval(function(){
      this.age++
    },100)
  }
};
</script>
<style type="text/css" media="all">
  .navigation{
    background: #ccc
  }
</style>