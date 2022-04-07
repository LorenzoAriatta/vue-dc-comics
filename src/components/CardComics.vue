<template>
  <div>
    <img :src="imgPath" alt="coverComics" />
    <h5>{{ series }}</h5>
  </div>
</template>

<script>
export default {
  name: "CardComics",
  props: {
    imgPath: String,
    series: String,
  },
};
</script>

<style>
</style>