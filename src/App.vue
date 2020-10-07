<template>
  <div id="app">
    <Header title="welcome Vue-cli"></Header>
    <Sidebar></Sidebar>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header";
import Sidebar from "./components/Sidebar";
import Footer from "./components/Footer";
export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    Footer
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
