<template>
   <navbar/>
   <cont/>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import navbar from './components/navbar.vue';
import cont from './components/cont.vue';

export default {
  name: 'App',
  components: {
    navbar,cont
  }
}
</script>

<style>
#app {
  font-family: 'Poppins', sans-serif;;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #FBF8CC;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
