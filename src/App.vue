<template>
  <div id="app">
    <Header></Header>
    <div class="main">
      <router-view name="slideBar"></router-view>
      <router-view name="main"></router-view>
    </div>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from './components/Header'
  import PostList from './components/PostList'
  import Article from './components/Article'
  import Footer from './components/Footer'
  

  export default {
    name: 'App',
    components: {
      Header,
      PostList,
      Footer
    }
  }
</script>

<style>
  * {
    margin: 0;
    padding: 0;
  }
  html {
    height: 100%;
  }
  body {
    height: 100%;
  }
  #app {
    min-height: 100%;
    background-color: #E1E1E1;
    display: flex;
    flex-direction: column;
  }
  .main {
    width: 85%;
    margin: 0 auto;
    flex: 1;
  }
</style>