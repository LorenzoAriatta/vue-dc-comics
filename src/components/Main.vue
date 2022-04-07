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
}
.main-container {
  width: 70%;
  margin: 0 auto;
  display: flex;
  flex-wrap: wrap;
  column-gap: 2%;
  row-gap: 50px;
  padding: 50px 0px;
}
</style>