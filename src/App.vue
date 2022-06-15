<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="header">
    <button @click="cnt++"> add list </button>
  </div>
  <div>
    <span> 신고 수 : {{cnt}} </span>
  </div>


</template>
  
  
<script>
export default {
  name: 'App',
  data(){
    return {
    cnt: 0,
    menu2: ['home','wish list', 'mypage'],
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

.header {
  display: flex;
  flex-direction: row;
  background: darkslateblue;
  align-items: center;
  justify-content: center;
  padding: 10px;
  margin-top: 5px;
}

.header a {
  color: #f8fbfb;
  font-size: 20px;
  font-weight: 600;
  text-decoration: none;
  margin: 0 10px;
}

</style>
