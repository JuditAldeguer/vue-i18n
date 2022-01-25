<template>
  <div id="app">
    <SwitchLang/>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloI18n/>
  </div>
</template>

<script>
import HelloI18n from './components/HelloI18n.vue'
import SwitchLang from './components/SwitchLang.vue'

export default {
  name: 'App',
  components: {
    HelloI18n, 
    SwitchLang
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
