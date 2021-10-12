<template>
  <div class="home">This is Home</div>
  <div class="heroSection">
    <img src="../assets/homehero.png" class="bgim" />
    <div class="overlaySection">
      <div class="logocol">
        <img src="../assets/logoOverlay.png" alt="Gabe A. Duhon" />
      </div>
      <div class="textCol">
        Experienced and Local <br />Attorneys Here for You
      </div>
    </div>
  </div>
  <div class="tabSection">
    <div class="tabs">
      <div class="tab-btn tab1">
        <p>Working With <b>Home Buyers</b></p>
      </div>
      <div class="tab-btn tab2">
        <p>Working With <b>Lenders</b></p>
      </div>
      <div class="tab-btn tab3">
        <p>Working With <b>Realtors</b></p>
      </div>
    </div>
    <div class="tabsImage">
      <img src="../assets/tabsSection1.png" alt="" />
      <img src="../assets/tabsSection2.png" alt="" />
    </div>
    <div class="tabsContent">
      <div class="tContent tab1Content">
        <div class="textLeft">Working with Home Buyers</div>
        <div class="textRight">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
          aliquam cursus metus, at accumsan massa ornare id. Aliquam facilisis
          ex aliquet, lacinia nunc at, semper nunc. Vivamus vel urna nec quam
          elementum ultricies. Vivamus sed sem venenatis nibh lacinia imperdiet
          sit amet sit amet ex. Nam vehicula venenatis odio, id feugiat libero
          gravida facilisis. Class aptent taciti sociosqu ad litora torquent per
          conubia nostra, per inceptos himenaeos. Donec commodo ex vitae odio
          tincidunt sodales vel at massa. Nulla facilisi. Etiam cursus varius
          urna, vel mattis sapien venenatis at. Donec et eros eros. Phasellus
          arcu mi, hendrerit eu nibh eu, condimentum iaculis sapien.
          <button class="btn learnMore">Learn More</button>
        </div>
      </div>
      <div class="tContent tab2Content">
        <div class="textLeft">Working with Lenders</div>

        <div class="textRight">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
          aliquam cursus metus, at accumsan massa ornare id. Aliquam facilisis
          ex aliquet, lacinia nunc at, semper nunc. Vivamus vel urna nec quam
          elementum ultricies. Vivamus sed sem venenatis nibh lacinia imperdiet
          sit amet sit amet ex. Nam vehicula venenatis odio, id feugiat libero
          gravida facilisis. Class aptent taciti sociosqu ad litora torquent per
          conubia nostra, per inceptos himenaeos. Donec commodo ex vitae odio
          tincidunt sodales vel at massa. Nulla facilisi. Etiam cursus varius
          urna, vel mattis sapien venenatis at. Donec et eros eros. Phasellus
          arcu mi, hendrerit eu nibh eu, condimentum iaculis sapien.
          <button class="btn learnMore">Learn More</button>
        </div>
      </div>
      <div class="tContent tab3Content">
        <div class="textLeft">Working with Realtors</div>
        <div class="textRight">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
          aliquam cursus metus, at accumsan massa ornare id. Aliquam facilisis
          ex aliquet, lacinia nunc at, semper nunc. Vivamus vel urna nec quam
          elementum ultricies. Vivamus sed sem venenatis nibh lacinia imperdiet
          sit amet sit amet ex. Nam vehicula venenatis odio, id feugiat libero
          gravida facilisis. Class aptent taciti sociosqu ad litora torquent per
          conubia nostra, per inceptos himenaeos. Donec commodo ex vitae odio
          tincidunt sodales vel at massa. Nulla facilisi. Etiam cursus varius
          urna, vel mattis sapien venenatis at. Donec et eros eros. Phasellus
          arcu mi, hendrerit eu nibh eu, condimentum iaculis sapien.
          <button class="btn learnMore">Learn More</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {},
};
</script>
<style scoped lang="scss">
//HeroSection
.heroSection {
  width: 100%;
  height: 80vh;
  position: relative;
  img.bgim {
    width: 100%;
    height: 100%;
  }
  .overlaySection {
    display: flex;
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    background-color: rgba(15, 18, 26, 0.9);
    padding: 30px 12px;
    height: 20vh;
    justify-content: right;
    align-items: center;
  }
  .logoCol {
    width: 30%;
  }
  .textCol {
    width: 60%;
    color: #fff;
    font-size: 70px;
  }
}
//tabsSection
.tabs {
  display: flex;
  justify-content: space-around;
  background-color: rgb(137, 36, 50);
  flex-wrap: wrap;
  color: #fff;
  font-size: 23px;
  text-transform: uppercase;
  padding-top: 15px;
  padding-bottom: 15px;
}
.tabsContent {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.tContent {
  display: flex;
  align-items: flex-start;
  .textLeft {
    width: 30%;
    font-size: 41px;
    color: #4f748b;
    line-height: 1;
  }
  .textRight {
    width: 70%;
    color: #707070;
  }
}
</style>
