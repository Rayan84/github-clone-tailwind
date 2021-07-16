<template>
  <div class="text-grey-900 text-sm">
     <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
      <navbar></navbar>
  
      <Main></Main>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue';
import Main from '@/components/Main.vue';

export default {
  name: 'App',
  components: {
    Main,
    Navbar
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
