<template>
  <div id="app">
    <Header></Header>
    <Contents></Contents>
    <Footer></Footer>
    <router-view/>
  </div>
</template>

<script>
import Header from './components/Header';
import Content from './components/Content';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
      Header,
      Contents: Content,
      Footer
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
