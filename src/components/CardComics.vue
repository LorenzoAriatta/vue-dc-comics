<template>
  <article>
    <div class="cards">
      <img :src="imgPath" alt="coverComics" />
      <p>{{ series }}</p>
    </div>
  </article>
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

<style lang="scss">
article {
  color: white;
  width: calc(100% / 6) - 2%;
  height: 230px;
}
.cards {
  width: 100%;
  height: 100%;
  img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: top;
  }
}
</style>