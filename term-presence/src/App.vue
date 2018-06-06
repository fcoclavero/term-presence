<template>
  <div id="app">
    <div class="container">
      <div class="Chart__list">
        <div class="Chart">
          <h2>Linechart</h2>
          <line-example></line-example>
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<script>
import Home from './components/Home.js'
export default {
  name: 'App',
  components: {
    Home
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
.container {
  max-width: 800px;
  margin:  0 auto;
}
</style>
