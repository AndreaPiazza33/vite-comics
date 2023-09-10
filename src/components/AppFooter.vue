<script>
export default {};
</script>

<template>
  <div class="footer-container">
    <!--parte azzurra del footer con img-->
    <div class="option-container">
      <div>
        <img src="" alt="" />
        <h4>DIGITAL COMICS</h4>
      </div>
      <div>
        <img src="" alt="" />
        <h4>DC MERCHANDISE</h4>
      </div>
      <div>
        <img src="" alt="" />
        <h4>SUBSCRIPTION</h4>
      </div>
      <div>
        <img src="" alt="" />
        <h4>COMIC SHOP LOCATOR</h4>
      </div>
      <div>
        <img src="" alt="" />
        <h4>DC POWER VISA</h4>
      </div>
    </div>
    <!--parte con img di background con lista-->
    <div class="list-container">
      <div class="list-box">
        <h4>DC COMICS</h4>
        <ul>
          <li>Characters</li>
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>Games</li>
          <li>Videos</li>
          <li>News</li>
        </ul>
        <h4>SHOP</h4>
        <ul>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
        </ul>
      </div>
      <div class="list-box">
        <h4>DC</h4>
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
      <div class="list-box">
        <h4>SITES</h4>
        <ul>
          <li>DC</li>
          <li>MAD Magazine</li>
          <li>DC Kids</li>
          <li>DC Universe</li>
          <li>DC Power Visa</li>
        </ul>
      </div>
      <div class="list-img-box">
        <img src="" alt="" />
      </div>
    </div>

    <!--parte finale con img e button-->
    <div class="bottom-footer-container">
      <div>
        <button>SIGN-UP NOW</button>
      </div>
      <div>
        <span>FOLLOW US</span>
        <img src="" alt="" />
        <img src="" alt="" />
        <img src="" alt="" />
        <img src="" alt="" />
        <img src="" alt="" />
      </div>
    </div>
  </div>
</template>
<style>
.footer-container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
}
.option-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  gap: 1.5rem;
  background-color: hsl(208.91deg 98.41% 49.22%);
}
.list-container {
  display: flex;
  flex-direction: row;
}
.list-box {
  width: calc(100% / 3);
}
.list-box ul {
  list-style-type: none;
}
.list-img-box {
  width: calc(2 * (100% / 3));
}
.bottom-footer-container {
  width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
</style>
