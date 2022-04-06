<template>
  <div id="app">
    <Header />
    <Main />
    <TopFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import TopFooter from "./components/TopFooter.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Main,
    TopFooter,
    Footer,
  },
};
</script>

<style lang="scss">
#app {
  margin: 30px 0px;
}
</style>
