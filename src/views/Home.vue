<template>
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
      <div class="tab-btn tab1" v-on:click="toggle = 1">
        <p>Working With <b>Home Buyers</b></p>
      </div>
      <div class="tab-btn tab2" v-on:click="toggle = 2">
        <p>Working With <b>Lenders</b></p>
      </div>
      <div class="tab-btn tab3" v-on:click="toggle = 3">
        <p>Working With <b>Realtors</b></p>
      </div>
    </div>
    <div class="tabsImage">
      <img src="../assets/tabsSection1.png" alt="" />
      <img src="../assets/tabsSection2.png" alt="" />
    </div>
    <div class="tabsContent">
      <div class="tContent tab1Content" v-show="toggle == 1">
        <div class="textLeft">Working with <br /><b>Home Buyers</b></div>
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
      <div class="tContent tab2Content" v-show="toggle == 2">
        <div class="textLeft">Working with <br /><b>Lenders</b></div>

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
      <div class="tContent tab3Content" v-show="toggle == 3">
        <div class="textLeft">Working with <br /><b>Realtors</b></div>
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
  <div class="whySection">
    <div class="titleWhy">
      <div class="images">
        <img src="../assets/whychooseus1.png" alt="" />
        <img src="../assets/whychooseus2.png" alt="" />
      </div>
      <div class="overlayTitle">
        <h2>WHY CHOOSE US</h2>
      </div>
    </div>
    <div class="contentWhy">
      <div class="container">
        <div class="col">
          <p class="comment">
            At the law office of Gabe A.<br />
            Duhon, LLC, attorneys Gabe A.<br />
            Duhon and Wyman E. Bankston are <br />proud to serve the citizens of
            Abbeville, Livingston and the rest of Acadiana with personalized
            local service since 2006.
          </p>
          <button class="btn learnMore">MEET OUR ATTORNEYS</button>
        </div>
        <div class="col spe">
          <div class="col1">
            <img src="../assets/person1.png" alt="" />
            <h3>GABE A. DUHON</h3>
            <p>ATTORNEY/OWNER</p>
          </div>
          <div class="col1">
            <img src="../assets/person2.png" alt="" />
            <h3>KIMBERLY K. SOURIYAKHAMPHONG</h3>
            <p>ASSOCIATE ATTORNEY</p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="contactUs">
    <div class="col">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam aliquam
        cursus metus, at accumsan massa ornare id. Aliquam facilisis ex aliquet,
        lacinia nunc at, semper nunc. Vivamus vel urna nec quam elementum
        ultricies. Vivamus sed sem venenatis nibh lacinia imperdiet sit amet sit
        amet ex. Nam vehicula venenatis odio, id feugiat libero gravida
        facilisis. Class aptent taciti sociosqu ad litora torquent per conubia
        nostra, per inceptos himenaeos. Donec commodo ex vitae odio tincidunt
        sodales vel at massa. Nulla facilisi. Etiam cursus varius urna, vel
        mattis sapien venenatis at. Donec et eros eros. Phasellus arcu mi,
        hendrerit eu
      </p>
    </div>
    <div class="col spe">
      <h3>CONTACT US</h3>
      <form>
        <div class="col1">
          <input
            type="text"
            placeholder="Name"
            name="name"
            style="margin-top: 0"
          />
          <input type="email" placeholder="Email" name="email" />
          <input
            type="phone"
            placeholder="Phone"
            name="phone"
            style="margin-bottom: 0"
          />
        </div>
        <div class="col2">
          <textarea placeholder="MESSAGE" name="message" />
          <button class="btn">Submit</button>
        </div>
      </form>
    </div>
  </div>
  <div class="lastSection">
    <div class="col1"><h3>Our Real Estate Title Services</h3></div>
    <div class="col2">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam aliquam
        cursus metus, at accumsan massa ornare id. Aliquam facilisis ex aliquet,
        lacinia nunc at, semper nunc. Vivamus vel urna nec quam elementum
        ultricies. Vivamus sed sem venenatis nibh lacinia imperdiet sit amet sit
        amet ex. Nam vehicula venenatis odio, id feugiat libero gravida
        facilisis. Class aptent taciti sociosqu ad litora torquent per conubia
        nostra, per inceptos himenaeos. Donec commodo ex vitae odio tincidunt
        sodales vel at massa. Nulla facilisi. Etiam cursus varius urna, vel
        mattis sapien venenatis at. Donec et eros eros. Phasellus arcu mi,
        hendrerit eu nibh eu, condimentum iaculis sapien.
      </p>
      <p>
        Donec eu blandit elit, in ultrices tellus. Maecenas ultricies bibendum
        sodales. Morbi in tincidunt eros. Vivamus nec ipsum suscipit, sagittis
        libero eget, vehicula leo. Aliquam erat volutpat. Donec auctor luctus
        diam, id finibus neque pellentesque vitae. Duis pretium ut velit quis
        cursus. Aliquam vitae leo nec neque luctus gravida. Nulla vestibulum,
        felis nec blandit lobortis, neque nisi aliquam nunc, eget vehicula
        lectus augue interdum leo. Nam vestibulum a sem id ornare. Praesent
        convallis mollis elementum.
      </p>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {},
  data() {
    return {
      toggle: 1
    }
  }
}
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
    padding: 30px 0px;
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
.tabSection {
  max-width: 1213px;
  margin: 0 auto 0 13%;
  .tab-btn {
    cursor: pointer;
  }
  .tabs {
    display: flex;
    flex-grow: 1;
    justify-content: space-around;
    background-color: rgb(137, 36, 50);
    flex-wrap: wrap;
    color: #fff;
    font-size: 19px;
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
    margin-top: 80px;
    .textLeft {
      width: 30%;
      font-size: 41px;
      color: #4f748b;
      line-height: 1;
      margin-right: 8%;
    }
    .textRight {
      width: 60%;
      color: #707070;
      font-size: 16px;
      text-align: left;
      line-height: 1.7;
    }
  }
}
.learnMore {
  border-radius: 0;
  border-top-left-radius: 5px;
  border-bottom-right-radius: 5px;
  border-color: #4f748b;
  border-width: 1px;
  background-color: #4f748b;
  padding: 5px 20px 5px 20px;
  color: #ffffff;
  font-weight: 600;
  font-size: 20px;
  line-height: 1.3;
  -webkit-transition: color 0.15s ease-in-out,
    background-color 0.15s ease-in-out, border-color 0.15s ease-in-out,
    -webkit-box-shadow 0.15s ease-in-out;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, -webkit-box-shadow 0.15s ease-in-out;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out,
    border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out,
    -webkit-box-shadow 0.15s ease-in-out;
  display: block;
  margin-top: 20px;
  margin-bottom: 20px;
  &:hover {
    background-color: #000000;
  }
}
//Why Choose Us
.whySection {
  margin-top: 50px;
  .titleWhy {
    position: relative;
    .images {
      display: flex;
      justify-content: flex-end;
    }
    .overlayTitle {
      position: absolute;
      bottom: 0;
      left: 45%;
      width: 60%;
      transform: translateX(-50%);
      background-color: #892432;

      color: #ffffff;
      padding: 10px;
      font-size: 40px;
      margin: 0 auto;
    }
  }
  .contentWhy {
    background-color: rgb(237, 237, 237);
    padding: 40px;
    display: flex;
    justify-content: center;
    padding-bottom: 300px;
    .container {
      max-width: 1200px;
      display: flex;
      justify-content: space-between;
      .col {
        width: 47%;
        p.comment {
          color: #4f748b;
          font-size: 40px;
          text-align: left;
        }
        &.spe {
          display: flex;
          justify-content: space-between;
          align-items: center;
        }
        .col1 {
          display: flex;
          flex-direction: column;
          width: 47%;
          h3 {
            margin-bottom: 0;
          }
          p {
            margin-top: 3px;
          }
        }
      }
    }
  }
}
//contact Section
.contactUs {
  background-color: rgb(112, 112, 112);
  padding: 80px 50px;
  max-width: 80%;
  margin: 0 auto;
  border-radius: 10px;
  display: flex;
  margin-top: -200px;
  .col {
    width: 47%;
    color: #ffffff;
    p {
      text-align: left;
      max-width: 70%;
      margin-top: 0;
    }
    h3 {
      font-size: 28px;
      font-weight: 400;
      text-align-last: left;
      margin-top: 0;
    }
    form {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-between;
      .col1 {
        width: 50%;
      }
      .col2 {
        width: 50%;
        text-align: right;
      }
      input {
        padding: 0.7rem 0.75rem;
        background-color: #ededed;
        display: block;
        max-width: 80%;
        width: 100%;
        border: 1px solid #ededed;
        margin: 15px 0;
        border-radius: 3px;
        font-size: 16px;
        -webkit-transition: border-color 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
        text-transform: uppercase;
      }
      textarea {
        margin-top: 0;
        padding: 0.7rem 0.75rem;
        background-color: #ededed;
        display: block;
        max-width: 92%;
        width: 100%;
        height: 85%;
        border: 1px solid #ededed;
        border-radius: 3px;
        font-size: 16px;
        -webkit-transition: border-color 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
        transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out,
          -webkit-box-shadow 0.15s ease-in-out;
      }
      button.btn {
        text-transform: uppercase;
        border-radius: 0;
        border-top-left-radius: 5px;
        border-bottom-right-radius: 5px;
        border-color: #ededed;
        border-width: 1px;
        background-color: #ededed;
        padding: 5px 20px 5px 20px;
        font-weight: 400;
        line-height: 1.5;
        color: #212529;
        text-align: center;
        font-size: 20px;
        margin-top: 10px;
        &:hover {
          background-color: #000000;
          color: #ffffff;
        }
      }
    }
  }
}
//lastSection
.lastSection {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 100px 0 70px 0;
  max-width: 1300px;
  margin: 0 auto;
  .col1 {
    width: 30%;
    h3 {
      font-size: 45px;
      font-weight: 400;
      color: #4f748b;
    }
  }
  .col2 {
    width: 60%;
    p {
      font-size: 16px;
      text-align: left;
      line-height: 1.5;
      color: #707070;
    }
  }
}
</style>
