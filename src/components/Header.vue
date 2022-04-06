<template>
  <header>
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
  </header>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  background-color: white;
  display: flex;
  justify-content: space-around;
  align-items: center;

  li {
    list-style-type: none;
    display: inline;
    margin: 1em;
    font-weight: bold;
    font-size: 14px;
    color: black;
  }
}
</style>
