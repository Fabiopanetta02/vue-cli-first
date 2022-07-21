<template>
  <div id="app">
    <H1 />
    <Div />
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Jumbotron from './components/Jumbotron.vue';
export default {
  name: 'App',
  components : {
    H1: Title,
    Div: Jumbotron
  }
  }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  margin-top: 60px;
}
</style>
