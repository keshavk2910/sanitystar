<template>
  <div class="titleSection">
    <h1>FAQ</h1>
  </div>
  <div class="accordionSection">
    <div class="container">
      <div class="col1">
        <h2>Commercial</h2>
        <div class="accordions">
          <div class="acctitle">QUESTION</div>
          <div class="answer">
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam
              aliquam cursus metus, at accumsan massa ornare id. Aliquam
              facilisis ex aliquet, lacinia nunc at, semper nunc. Vivamus vel
              urna nec quam elementum ultricies. Vivamus sed sem venenatis nibh
              lacinia imperdiet sit amet sit amet ex. Nam vehicula venenatis
              odio, id feugiat libero gravida facilisis. Class aptent taciti
              sociosqu ad litora torquent per conubia nostra, per inceptos
              himenaeos. Donec commodo ex vitae odio tincidunt sodales vel at
              massa. Nulla facilisi. Etiam cursus varius urna, vel mattis sapien
              venenatis at. Donec et eros eros. Phasellus arcu mi, hendrerit eu
              nibh eu, condimentum iaculis sapien.
            </p>
          </div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
          <div class="acctitle">QUESTION</div>
        </div>
      </div>
      <div class="col2">
        <div class="col2area">
          <h2>Practice Areas</h2>
          <ul>
            <li>COMMERCIAL</li>
            <li>RESIDENTIAL</li>
            <li>TITLE SETTLEMENT</li>
            <li>ESTATE PLANNING</li>
            <li>LOAN CLOSING</li>
          </ul>
        </div>
      </div>
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

<script>
export default {
  components: {}
}
</script>

<style lang="scss" scoped>
.titleSection {
  font-size: 45px;
  background-color: #060f21;
  color: #ffffff;
  padding: 100px 0;
  h1 {
    font-weight: 400;
  }
}

.accordionSection {
  .acctitle {
    font-size: 20px;
    border-top: 1px solid #dfdfdf;
    padding-top: 10px;
    margin-bottom: 13px;
  }

  .container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    max-width: 1300px;
    margin: 0 auto;
  }
  background-color: #16223b;
  padding: 50px 0;

  color: #fff;
  .col1 {
    width: 55%;
    text-align: left;
  }
  .col2 {
    width: 30%;
    position: relative;
  }
  .col2area {
    width: 100%;
    text-align: left;
    background-color: #415f77;
    padding: 80px 60px;
    position: absolute;
    top: -20%;
    ul {
      list-style: none;
      text-align: left;
      padding: 0;
      li {
        padding-bottom: 15px;
      }
    }
  }
  h2 {
    font-size: 45px;
    font-weight: 400;
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
