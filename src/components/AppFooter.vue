<script>
export default {
  data() {
    return {
      optionContainer: [
        {
          image: "/img/buy-comics-digital-comics.png",
          option: "DIGITAL COMICS",
        },
        {
          image: "/img/buy-comics-merchandise.png",
          option: "DC MERCHANDISE",
        },
        {
          image: "/img/buy-comics-subscriptions.png",
          option: "SUBSCRIPTION",
        },
        {
          image: "/img/buy-comics-shop-locator.png",
          option: "COMIC SHOP LOCATOR",
        },
        {
          image: "/img/buy-dc-power-visa.svg",
          option: "DC POWER VISA",
        },
      ],
      socialContainer: [
        {
          socialIcon: "/img/footer-facebook.png",
        },
        {
          socialIcon: "/img/footer-twitter.png",
        },
        {
          socialIcon: "/img/footer-youtube.png",
        },
        {
          socialIcon: "/img/footer-pinterest.png",
        },
        {
          socialIcon: "/img/footer-periscope.png",
        },
      ],
    };
  },
};
</script>

<template>
  <div class="footer-container">
    <!--parte azzurra del footer con img-->
    <div class="option-container">
      <div class="option-box" v-for="img in optionContainer">
        <img :src="img.image" alt="" />
        <h4>{{ img.option }}</h4>
      </div>
    </div>
    <!--parte con img di background con lista-->
    <div class="list-container">
      <div class="list-box">
        <div>
          <h3>DC COMICS</h3>
          <ul>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>TV</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <h3>SHOP</h3>
          <ul>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
          </ul>
        </div>
        <div>
          <h3>DC</h3>
          <ul>
            <li>Term Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscription</li>
            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Show Help</li>
            <li>Contact Us</li>
          </ul>
        </div>
        <div>
          <h3>SITES</h3>
          <ul>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>

      <div>
        <img src="\img\dc-logo-bg.png" alt="" />
      </div>
    </div>

    <!--parte finale con img e button-->
    <div class="bottom-footer-container">
      <div>
        <button>SIGN-UP NOW!</button>
      </div>
      <div class="bottom-icon-box">
        <span>FOLLOW US</span>
        <div v-for="icon in socialContainer">
          <img :src="icon.socialIcon" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.footer-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
/*parte superiore footer*/
.option-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(208.91deg 98.41% 49.22%);
  padding: 0 10rem;
}
.option-box {
  display: flex;
  flex-direction: row;
  align-items: center;
  color: white;
  padding: 3rem 0;
  img {
    height: 50px;
    width: 50px;
  }
}

/*parte centrale footer*/
.list-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  background-image: url("/img/footer-bg.jpg");
  img {
    max-height: 400px;
  }
}

.list-box {
  display: flex;
  flex-direction: row;
  gap: 2rem;
  h3 {
    color: white;
    margin-top: 2rem;
    margin-bottom: 1rem;
  }
  ul {
    color: hsl(0, 0%, 64%);
    list-style-type: none;
  }
}

/*parte finale del footer*/
.bottom-footer-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
  background-color: hsl(0deg 0% 18.82%);
  padding: 1rem 1rem;
  button {
    border: 2px solid hsl(208.91deg 98.41% 49.22%);
    background-color: hsl(0deg 0% 18.82%);
    color: white;
    padding: 0.5rem 0.5rem;
  }
}

.bottom-icon-box {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 1rem;
  span {
    color: hsl(208.91deg 98.41% 49.22%);
    font-weight: bolder;
  }
}
</style>
