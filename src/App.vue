<template>
<div id="app">
<header>
<dropdown />
</header>

</div>


</template>

<script>
import dropdown from "./components/dropdown.vue"



export default {
  name: 'App',
  components: {
    dropdown

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
