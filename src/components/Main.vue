<template>
  <main>
    <div class="main-container">
      <CardComics
        v-for="(item, index) in Comics"
        :key="'prod-' + index"
        :imgPath="item.thumb"
        :series="item.series"
      />
    </div>
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
  background-color: black;
  color: white;
  background-color: #1c1c1c;
}
.main-container {
  width: 70%;
  margin: 0 auto;
  text-align: left;
  line-height: 150px;
  height: 150px;
}
</style>