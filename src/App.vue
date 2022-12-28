<template>
  <profile-content></profile-content>
</template>

<script>
import ProfileContent from "./components/ProfileContent.vue"

export default {
  name: 'App',
  components: {
    ProfileContent
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
