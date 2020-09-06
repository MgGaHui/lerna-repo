<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <package-test></package-test>
  </div>
</template>

<script>
import PackageTest from '../packages/package-test'

export default {
  name: 'App',
  components: {
    'package-test':PackageTest
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
