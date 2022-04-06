<template>
  <header>
    <div class="head-container">
      <img src="../assets/dc-logo.png" alt="DC-Logo" />
      <ul>
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "HeaderSection",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  background-color: white;
}
.head-container {
  width: 80%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 0px;
  margin: 0 auto;
  li {
    list-style-type: none;
    display: inline;
    margin: 1em;
    font-weight: bold;
    font-size: 14px;
  }
}
</style>
