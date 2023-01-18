<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <SyMain msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import SyMain from './components/SyMain.vue'

export default {
  name: 'App',
  components: {
    SyMain
  }
}
</script>

<style>
#app {
  display: flex;
  flex-flow: wrap;
} 

</style>
