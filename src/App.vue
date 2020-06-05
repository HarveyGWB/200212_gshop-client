<template>
  <div id="app">
    <Header></Header>
    <router-view></router-view>

    <footer></footer>
  </div>
</template>

<script type="text/ecmascript-6">
import Header from "./components/Header";
import Footer from "./components/Footer";

export default {
  comments: {
    Header,
    Footer
  }
};
</script>

<style scoped>
</style>
