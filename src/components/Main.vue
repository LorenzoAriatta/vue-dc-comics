<template>
  <main>
    <div class="jumbo"></div>
    <div class="main-container">
      <div class="flydiv"><h2>CURRENT SERIES</h2></div>
      <CardComics
        v-for="(item, index) in Comics"
        :key="'prod-' + index"
        :imgPath="item.thumb"
        :series="item.series"
      />
    </div>
    <button>LOAD MORE</button>
  </main>
</template>

<script>
import CardComics from "@/components/CardComics.vue";

export default {
  name: "MainSection",
  props: {
    Comics: Array,
  },
  components: {
    CardComics,
  },
};
console.log(CardComics);
</script>

<style scoped lang="scss">
main {
  background-color: #1c1c1c;
  display: flex;
  flex-direction: column;
}
.main-container {
  width: 70%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  column-gap: 2%;
  row-gap: 50px;
  padding: 50px 0px;
  position: relative;
}
.jumbo {
  width: 100%;
  height: 40vh;
  background-image: url(../assets/jumbotron.jpg);
  background-repeat: no-repeat;
  background-position: top;
}
.flydiv {
  position: absolute;
  top: -4%;
  left: 0%;
  background-color: #0282f9;
  padding: 10px 30px;
  color: white;
}
button {
  margin: 30px 0px;
  width: 200px;
  padding: 10px;
  color: white;
  background-color: #0282f9;
  border: 0;
  font-weight: bold;
  align-self: center;
  &:hover {
    transition: 0.5s;
    box-shadow: 0px 0px 25px 5px #0282f9;
    background-color: #1c1c1c;
    border-radius: 25px;
  }
}
</style>