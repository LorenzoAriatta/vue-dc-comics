<template>
  <div id="app">
    <Header />
    <Main :Comics="Comics" />
    <TopFooter />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import TopFooter from "./components/TopFooter.vue";
import Footer from "./components/Footer.vue";

//import data
import Comics from "@/assets/data/dc-comics";

export default {
  name: "App",
  data() {
    return {
      Comics,
    };
  },
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
