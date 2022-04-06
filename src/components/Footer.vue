<template>
  <footer>
    <div id="main-footer" class="container">
      <div class="info">
        <div class="list">
          <h3>DC COMICS</h3>
          <ul>
            <li>
              <a href="#">Characters</a>
            </li>
            <li>
              <a href="#">Comics</a>
            </li>
            <li>
              <a href="#">Movies</a>
            </li>
            <li>
              <a href="#">TV</a>
            </li>
            <li>
              <a href="#">Games</a>
            </li>
            <li>
              <a href="#">Videos</a>
            </li>
            <li>
              <a href="#">News</a>
            </li>
          </ul>
        </div>
        <div class="list">
          <h3>SHOP</h3>
          <ul>
            <li>
              <a href="#">Shop DC</a>
            </li>
            <li>
              <a href="#">Shop DC Collectibles</a>
            </li>
          </ul>
        </div>
        <div class="list">
          <h3>DC</h3>
          <ul>
            <li>
              <a href="#">Terms Of Use</a>
            </li>
            <li>
              <a href="#">Privacy Policy (New)</a>
            </li>
            <li>
              <a href="#">Ad Choices</a>
            </li>
            <li>
              <a href="#">Advertising</a>
            </li>
            <li>
              <a href="#">Jobs</a>
            </li>
            <li>
              <a href="#">Subscriptions</a>
            </li>
            <li>
              <a href="#">Talent Workshops</a>
            </li>
            <li>
              <a href="#">CPSC Certificates</a>
            </li>
            <li>
              <a href="#">Ratings</a>
            </li>
            <li>
              <a href="#">Shop Help</a>
            </li>
            <li>
              <a href="#">Contact Us</a>
            </li>
          </ul>
        </div>
        <div class="list">
          <h3>SITES</h3>
          <ul>
            <li>
              <a href="#">DC</a>
            </li>
            <li>
              <a href="#">MAD Magazine</a>
            </li>
            <li>
              <a href="#">DC Kids</a>
            </li>
            <li>
              <a href="#">DC Universe</a>
            </li>
            <li>
              <a href="#">DC Power Vista</a>
            </li>
          </ul>
        </div>
      </div>
      <img src="../assets/dc-logo-bg.png" alt="DC Logo" />
    </div>
    <div id="bot-footer" class="container"></div>
  </footer>
</template>

<script>
export default {
  name: "FooterSection",
};
</script>

<style scoped lang="scss">
footer {
  background-image: url(../assets/footer-bg.jpg);
  background-repeat: no-repeat;
  background-size: cover;
}
#main-footer {
  display: flex;
  justify-content: space-around;
}
.info {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  .list {
    margin-bottom: 15px;
    h3 {
      color: white;
      margin-bottom: 15px;
    }
    li {
      list-style-type: none;
    }
    a {
      text-decoration: none;
      color: #959595;
      font-size: 12px;
    }
  }
}
</style>