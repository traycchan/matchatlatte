<template>
  <div id="app">
    <div class="body">
      <HelloWorld msg="One Fine Day "/>
      <img alt="Vue logo" src="./assets/logo.jpg">
    </div>
    <div class="sidebar">
      <button-panel/>
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ButtonPanel from './components/ButtonPanel.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    ButtonPanel
  }
}
</script>

<style>
#app {
  display: flex;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
