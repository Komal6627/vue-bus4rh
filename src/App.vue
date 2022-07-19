<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->

    <!-- <Sample  data="This is props data"/>
    <Home /> -->
    <Temp />

  </div>
</template>

<script>


import Temp from './components/Temp.vue'

export default {
  name: 'App',
  components: {
    Temp
  },
};
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
