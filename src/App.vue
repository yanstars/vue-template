<template>
  <div id="app">
    <img src="./assets/logo.png">
    <p>{{'aaaa'}}</p>
  </div>
</template>

<script>
export default {
  name: 'App',
  created () {
    let a = 'ceshi'
    this.name()
    console.log( null ?? a);
  },
  methods: {
   async  name() {

     this
     console.error(this)
     debugger
      
    }
  },
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
