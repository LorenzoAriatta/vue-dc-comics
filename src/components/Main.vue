<template>
  <main>
    <div class="main-container">
      <!-- <div v-for="(item, index) in Comics" :key="'prod-' + index">
        <img :src="item.thumb" alt="artcover" />
        <h5>{{ item.series }}</h5>
      </div> -->
      <Comics v-for="(item, index) in Comics" :key="'prod-' + index" />
    </div>
  </main>
</template>

<script>
export default {
  name: "MainSection",
  props: {
    Comics: Array,
  },
};
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