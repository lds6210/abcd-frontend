<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <div>
    {{logo}}
    <h4> XX 원룸 </h4>
    <p> {{price1}}만원 </p>
  </div>
  <div>
    <h3> {{products[0]}} </h3>
    <h4> XX 원룸 </h4>
    <p> {{price2}} 만원 </p>
  </div>
</template>
  
  
<script>
export default {
  name: 'App',
  data(){
    return {
      price1 : 60,
      price2 : 80,
      logo : "燮雲",
      products : ['1','2','3'],
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
  margin-top: 60px;
}
</style>
