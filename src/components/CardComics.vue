<template>
  <div class="cards">
    <img :src="imgPath" alt="coverComics" />
    <h5>{{ series }}</h5>
  </div>
</template>

<script>
export default {
  name: "CardComics",
  props: {
    comic: Object,
    imgPath: String,
    series: String,
  },
};
</script>

<style>
.cards {
  width: 100%;
}
</style>