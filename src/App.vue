<template>
  <div id="app">
    <h1>It's me, Max!</h1>
    <img src="./assets/personal-pic.png"> 
    <YearViewer msg = "View by Year"/>
  </div>
</template>

<script>
import YearViewer from './components/YearViewer'

export default {
  name: 'app',
  components: {
    YearViewer
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
