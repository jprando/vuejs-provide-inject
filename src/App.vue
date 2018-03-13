<template>
  <div id="app">
    <comp01 />
  </div>
</template>

<script>
  import Comp01 from './components/comp01'

  export default {
    name: 'App',
    components: { Comp01 },
    mounted () {
      console.clear()
    }
  };
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
