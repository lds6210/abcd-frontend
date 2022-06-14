<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="menu">
    <a v-for = "i in menu2" :key="i"> {{i}} </a>
  </div>
  
</template>
  
  
<script>
export default {
  name: 'App',
  data(){
  return {
    menu2: ['home','want to list', 'want the list','mypage'],
    }
  },
  components: {
    
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.menu {
  display: flex;
  flex-direction: row;
  background: darkslateblue;
  align-items: center;
  justify-content: center;
  padding: 10px;
  margin-top: 5px;
}

.menu a {
  color: #f8fbfb;
  font-size: 20px;
  font-weight: 600;
  text-decoration: none;
  margin: 0 10px;
}

</style>
