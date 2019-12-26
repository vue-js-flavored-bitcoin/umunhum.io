<template>
  <div id="app">

    <p>Project Umunhum - Pacific Bay Bitcoin</p>

    <p>a set of bitcoin libraries, written in multiple languages<br/><br/>
      <a href="https://github.com/rust-flavored-bitcoin/umunhum">Rust</a>, <a href="https://github.com/scala-flavored-bitcoin/umunhum">Scala</a></p>
    <br/>
    <a href="https://github.com/rust-flavored-bitcoin/umunhum">
      <img src="./assets/umunhum.jpg" height="169" width="300"/><br/>
    </a>
    <br/>


    <div><Welcome/></div>

  </div>

</template>

<script>
import Welcome from './components/Welcome'

export default {
  name: 'App',
  components: {
    Welcome
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
