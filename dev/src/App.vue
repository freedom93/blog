<template>
  <div id="app">
    <header></header>
    <router-view></router-view>
    <footer></footer>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style lang ='scss'>
@import "./assets/commons/css/mixin";
@import "./assets/commons/css/normalize";
@import "./assets/commons/css/reset";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
