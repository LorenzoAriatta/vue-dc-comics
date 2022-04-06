<template>
  <header>
    <div class="head-container">
      <img src="../assets/dc-logo.png" alt="DC-Logo" />
      <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
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
  width: 70%;
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
    font-size: 12px;
    padding-bottom: 49px;
    &:hover {
      border-bottom: 4px solid #0282f9;
    }
    a {
      text-decoration: none;
      color: #464646;
    }
  }
}
li:hover a {
  color: #0282f9;
}
</style>
