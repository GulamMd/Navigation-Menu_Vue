<template>
  <NavigationMenu/>
</template>

<script>
import NavigationMenu from './components/NavigationMenuPage.vue'

export default {
  name: 'App',
  components: {
    NavigationMenu
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
