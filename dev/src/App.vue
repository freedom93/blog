<template>
  <div id='app'>
    <!-- <navigation/> -->
    <router-view></router-view>
    <!-- <pagefooter></pagefooter> -->
  </div>
</template>

<script>
import Navigation from '@/components/Navigation'
import Pagefooter from '@/components/Pagefooter'

export default {
  name: 'app',
  components: {
    Navigation, Pagefooter
  }
}
</script>

<style lang ='scss'>
/*@import './assets/commons/css/mixin';*/
/*@import './assets/commons/css/normalize';*/
/*@import './assets/commons/css/reset';*/
@import './assets/scss/variables.scss';
@import './assets/scss/mixins.scss';
@import './assets/scss/global.scss';
@import './assets/scss/navbar.scss';
@import './assets/scss/masthead.scss';
@import './assets/scss/post.scss';
@import './assets/scss/contact.scss';
@import './assets/scss/footer.scss';
@import './assets/scss/bootstrap-overrides.scss';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
