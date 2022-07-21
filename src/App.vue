<template>
  <div id="app">
    <Title />
  </div>
</template>

<script>
import Title from './components/Title.vue'
export default {
  name: 'App',
  components : {
    Title: Title
  }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
