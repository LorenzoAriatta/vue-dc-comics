<template>
  <footer>
    <div class="container">
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
      <div class="logo-bg"></div>
    </div>
    <div id="bot-footer">
      <div class="container-bot">
        <button>SIGN-UP NOW!</button>
        <div class="social">
          <h3>FOLLOW US</h3>
          <div class="icon-social">
            <img src="../assets/footer-facebook.png" alt="Facebook" />
          </div>
          <div class="icon-social">
            <img src="../assets/footer-twitter.png" alt="twitter" />
          </div>
          <div class="icon-social">
            <img src="../assets/footer-youtube.png" alt="youtube" />
          </div>
          <div class="icon-social">
            <img src="../assets/footer-pinterest.png" alt="pinterest" />
          </div>
          <div class="icon-social">
            <img src="../assets/footer-periscope.png" alt="periscope" />
          </div>
        </div>
      </div>
    </div>
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
.container {
  width: 70%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}
.info {
  display: flex;
  column-gap: 3em;
  padding: 40px 0px;
  .list {
    margin-bottom: 15px;
    h3 {
      color: white;
      margin: 15px 0px;
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
.logo-bg {
  background-image: url(../assets/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: center;
  width: 40%;
}
#bot-footer {
  background-color: #303030;
  padding: 30px 0px;
  .social {
    display: flex;
    align-items: center;
    column-gap: 1em;
    h3 {
      color: #0282f9;
    }
  }
}
.container-bot {
  width: 70%;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
}
button {
  border: 2px solid #0282f9;
  background-color: #303030;
  padding: 15px 15px;
  color: white;
  font-size: 16px;
  font-weight: bold;
}
</style>