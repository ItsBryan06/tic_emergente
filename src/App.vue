<template>
  <v-app>
    <router-view> 

    </router-view>
    
  </v-app>
</template>
<script>

export default {
  name: 'App', 
  components: {
    
  },

  data: () => {
  
    return {
          
    
    };
  }
};
</script>

<style>

#app {
  background: url('./assets/Background/Fondo_inicio.png') no-repeat center center fixed !important;
  background-size: cover;
  
}

.title {
color:  white;
text-align: right;
position: relative;
  bottom: -200px;
   right: 200px;


}

.subtitle {
  color:  white;
text-align: right;
position: relative;
  bottom: -220px;
   right: 170px;
   font-size: 35px;
  

}

body{
  margin: 0; 
  padding: 0;
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}

.icon {
    align-content: right;
    align-items: right;
    padding-left: 85%;
    position: relative;
  bottom: 190px;
   right: 300px;
   font-size: 50px;
    

}
    

</style>
