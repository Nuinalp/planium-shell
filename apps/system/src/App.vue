<template>
  <div id="app">
    <DesktopEnvironment/>
  </div>
</template>

<script>
import DesktopEnvironment from './components/DesktopEnvironment'

export default {
  name: 'App',
  components: {
    DesktopEnvironment
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
