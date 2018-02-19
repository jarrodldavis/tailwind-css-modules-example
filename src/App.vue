<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Example />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Example from './components/Example.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Example
  }
}
</script>

<style lang="postcss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

@tailwind preflight;
@tailwind utilities;
</style>
