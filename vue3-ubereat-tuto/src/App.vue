<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}


</script>

<style>
@import url(style/reset.css);
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500&display=swap');
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  padding: 0 20px;
}
</style>
