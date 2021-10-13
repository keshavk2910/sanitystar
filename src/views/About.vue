<template>
  <div class="heroSection">
    <img src="../assets/aboutHero.png" alt="About Us" />
  </div>
  <div class="fullOverlay">
    <div class="titleSection">
      <h1>About Us</h1>
    </div>
    <div class="goodContainer">
      <div class="aboutText">
        Vestibulum Mattis Laoreet Est, Scelerisque<br />
        Hehicula Enim Laoreet
      </div>
    </div>
    <div class="personSection">
      <div class="col">
        <img src="../assets/person1.png" alt="GABE A. DUHON" />
        <h2>GABE A. DUHON</h2>
        <p class="position">ATTORNEY/OWNER</p>
        <div class="textDiv">
          <p class="mt58">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
            aliquam cursus metus, at accumsan massa ornare id. Aliquam facilisis
            ex aliquet, lacinia nunc at, semper nunc. Vivamus vel urna nec quam
            elementum ultricies. Vivamus sed sem venenatis nibh lacinia
            imperdiet sit amet sit amet ex. Nam vehicula venenatis odio, id
            feugiat libero gravida facilisis. Class aptent taciti sociosqu ad
            litora torquent per conubia nostra, per inceptos himenaeos. Donec
            commodo ex vitae odio tincidunt sodales vel at massa. Nulla
            facilisi. Etiam cursus varius urna, vel mattis sapien venenatis at.
            Donec et eros eros. Phasellus arcu mi, hendrerit eu nibh eu,
            condimentum iaculis sapien.
          </p>
          <p>
            Donec eu blandit elit, in ultrices tellus. Maecenas ultricies
            bibendum sodales. Morbi in tincidunt eros. Vivamus nec ipsum
            suscipit, sagittis libero eget, vehicula leo. Aliquam erat volutpat.
            Donec auctor luctus diam, id finibus neque pellentesque vitae. Duis
            pretium ut velit quis cursus. Aliquam vitae leo nec neque luctus
            gravida. Nulla vestibulum, felis nec blandit lobortis, neque nisi
            aliquam nunc, eget vehicula lectus augue interdum leo. Nam
            vestibulum a sem id ornare. Praesent convallis mollis elementum.
          </p>
        </div>
        <div class="cred">CREDENTIALS<span class="expand">EXPAND</span></div>
      </div>
      <div class="col">
        <img src="../assets/person2.png" alt="KIMBERLY K. SOURIYAKHAMPHONG" />
        <h2>
          KIMBERLY K. <br />
          SOURIYAKHAMPHONG
        </h2>
        <p class="position">ASSOCIATE ATTORNEY</p>
        <div class="textDiv">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
            aliquam cursus metus, at accumsan massa ornare id. Aliquam facilisis
            ex aliquet, lacinia nunc at, semper nunc. Vivamus vel urna nec quam
            elementum ultricies. Vivamus sed sem venenatis nibh lacinia
            imperdiet sit amet sit amet ex. Nam vehicula venenatis odio, id
            feugiat libero gravida facilisis. Class aptent taciti sociosqu ad
            litora torquent per conubia nostra, per inceptos himenaeos. Donec
            commodo ex vitae odio tincidunt sodales vel at massa. Nulla
            facilisi. Etiam cursus varius urna, vel mattis sapien venenatis at.
            Donec et eros eros. Phasellus arcu mi, hendrerit eu nibh eu,
            condimentum iaculis sapien.
          </p>
          <p>
            Donec eu blandit elit, in ultrices tellus. Maecenas ultricies
            bibendum sodales. Morbi in tincidunt eros. Vivamus nec ipsum
            suscipit, sagittis libero eget, vehicula leo. Aliquam erat volutpat.
            Donec auctor luctus diam, id finibus neque pellentesque vitae. Duis
            pretium ut velit quis cursus. Aliquam vitae leo nec neque luctus
            gravida. Nulla vestibulum, felis nec blandit lobortis, neque nisi
            aliquam nunc, eget vehicula lectus augue interdum leo. Nam
            vestibulum a sem id ornare. Praesent convallis mollis elementum.
          </p>
        </div>
        <div class="cred">CREDENTIALS<span class="expand">EXPAND</span></div>
      </div>
    </div>
  </div>
  <div class="cras">
    <div class="textBox">
      CRAS ET<br />FRINGILLA<br />LIBERO <button>CONTACT US TODAY</button>
    </div>
    <div class="imageDiv">
      <img src="../assets/aboutimage1.png" alt="" />
      <img src="../assets/aboutimage2.png" alt="" />
    </div>
  </div>
  <div class="reviewSection">
    <div class="review">
      <p>
        Suspendisse dignissim ultrices dolor, quis condimentum orci. Proin eu
        pulvinar leo. Quisque tempor aliquet convallis. Ut in urna lacinia,
        viverra ex quis, suscipit sapien. Donec sed ipsum velit. Praesent at
        faucibus purus. Curabitur pretium nibh vel nisi efficitur viverra.
        Nullam finibus in lectus ut fermentum. Phasellus hendrerit nec nulla a
        posuere. Fusce rhoncus ut sem et lobortis. Aenean tempus ut neque eu
        eleifend. Curabitur quis urna mi. Suspendisse odio justo, lobortis vel
        auctor ut, ornare eget tortor. <br />LOREM IPSUM
      </p>
    </div>
  </div>
  <div class="contanier">
    <img
      src="../assets/aboutcontact.png"
      alt="Contact Us"
      class="contactBefore"
    />
    <div class="contactUs">
      <div class="col">
        <h2>Contact Us <br />Today!</h2>
      </div>
      <div class="col spe">
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
  </div>
</template>

<style lang="scss" scoped>
.heroSection img {
  width: 100%;
  z-index: -1;
  position: relative;
}
.fullOverlay {
  margin-top: -37%;
}
.goodContainer {
  margin: 0 auto;
  max-width: 1300px;
}
.titleSection {
  background-color: rgba(10, 21, 41, 0.6);
  padding: 80px 0;
  margin-bottom: 20px;
  h1 {
    color: #ffffff;
    font-size: 65px;
    font-weight: 400;
  }
}
.aboutText {
  color: #4f748b;
  font-size: 45px;
  text-align: left;
  margin-bottom: 50px;
}
.personSection {
  display: flex;
  flex-wrap: wrap;
  max-width: 1300px;
  margin: 0 auto;
  justify-content: space-between;
  .col {
    width: 47%;
    text-align: left;
    h2 {
      color: #4f748b;
      font-weight: 400;
      font-size: 30px;
      text-align: left;
      margin-bottom: 3px;
    }
    p.position {
      color: #4f748b;
      text-align: left;
      margin-top: 0;
    }
    img {
      width: 250px;
    }
    .mt58 {
      margin-top: 58px;
    }
  }
  .cred {
    padding-top: 3px;
    padding-bottom: 15px;
    font-size: 25px;
    color: #892432;
    border-top: 1px solid #000;
    border-bottom: 1px solid #000;
    position: relative;
    .expand {
      position: absolute;
      bottom: 0;
      right: 0;
      font-size: 14px;
      color: #4f748b;
    }
  }
}
//cras section
.cras {
  margin-top: 50px;
  position: relative;
  padding-top: 300px;
  .textBox {
    background-color: #892432;
    color: #ffffff;
    font-size: 60px;
    font-weight: 500;
    max-width: 600px;
    width: 600px;
    padding: 70px;
    line-height: 1.2;
    text-align: left;
    position: absolute;
    right: 20%;
    top: 10%;
    button {
      display: block;
      margin-top: 20px;
      color: #4f748b;
      padding: 5px 10px;
      border-radius: 2px;
      border: none;
      font-size: 14px;
      font-weight: 500;
    }
  }
  .imageDiv {
    img {
      width: 50%;
    }
  }
}
.reviewSection {
  display: flex;
  flex-wrap: wrap;
  justify-content: flex-end;
  max-width: 1300px;
  padding: 50px 0;
  .review {
    width: 50%;
    font-size: 18px;
    text-align: left;
    line-height: 1.7;
  }
}
//contact Section
.contactUs {
  padding: 20px 0;
  max-width: 100%;
  margin: 0 auto;
  border-radius: 10px;
  display: flex;
  .col {
    &.spe {
      width: 70%;
    }
    width: 30%;
    color: #4f748b;
    p {
      text-align: left;
      max-width: 70%;
      margin-top: 0;
    }
    h2 {
      font-size: 45px;
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
img.contactBefore {
  width: 100%;
}
.contanier {
  max-width: 1300px;
  margin: 0 auto;
}
</style>
