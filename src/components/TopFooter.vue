<template>
  <div id="top-footer">
    <div class="top-footer-container">
      <div class="links">
        <img
          src="../assets/buy-comics-digital-comics.png"
          alt="Digital Comics"
        />
        <h4><a href="#">DIGITAL COMICS</a></h4>
      </div>
      <div class="links">
        <img
          src="../assets/buy-comics-merchandise.png"
          alt="Comics Merchandise"
        />
        <h4><a href="#">DC MERCHANDISE</a></h4>
      </div>
      <div class="links">
        <img
          src="../assets/buy-comics-subscriptions.png"
          alt="Comics Merchandise"
        />
        <h4><a href="#">SUBSCRIPTION</a></h4>
      </div>
      <div class="links">
        <img
          src="../assets/buy-comics-shop-locator.png"
          alt="Comics Merchandise"
        />
        <h4><a href="#">COMIC SHOP LOCATOR</a></h4>
      </div>
      <div class="links">
        <img src="../assets/buy-dc-power-visa.svg" alt="Comics Merchandise" />
        <h4><a href="#">COMIC SHOP LOCATOR</a></h4>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TopFooter",
};
</script>

<style scoped lang="scss">
#top-footer {
  background-color: #0282f9;
}
.top-footer-container {
  width: 80%;
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 50px 0px;
  margin: 0 auto;

  .links {
    display: flex;
    align-items: center;
    column-gap: 1rem;
    img {
      width: 40px;
      height: 50px;
    }
    a {
      text-decoration: none;
      color: white;
      font-weight: initial;
    }
  }
}
</style>