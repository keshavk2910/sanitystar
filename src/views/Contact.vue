<template>
  <div class="overlay">
    <div class="title">Contact Us</div>
  </div>
  <div class="main-container">
    <div class="red-container">
      <div class="content">
        <div class="title">
          Schedule a <br />
          Consultation
        </div>
        <!-- Basic form field can be used commonly -->
        <div class="form">
          <div class="req-f">REQUIRED FIELDS*</div>
          <input v-model="message" placeholder="NAME*" />
          <input v-model="message" placeholder="EMAIL*" />
          <input v-model="message" placeholder="PHONE*" />
          <input v-model="message" placeholder="SERVICE/SUBJECT" />
          <textarea v-model="message" placeholder="MESSAGE"></textarea>
        </div>
      </div>
      <div class="right-image">
        <img src="../assets/consulting.png" alt="consult" />
      </div>
    </div>
    <!-- MAP AND ADDRESS LINES -->
    <div class="map-address">
      <div class="map">
        <img src="../assets/map.png" alt="" />
      </div>
      <div class="address">
        105 Tivoli Street <br />
        Abbeville, LA <br />337-893-3423
      </div>
    </div>
    <!-- some description about us -->
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
  </div>
</template>

<style scoped lang="scss">
// Common header for other than home
.main-container {
  // common page layout
  box-sizing: border-box;
  max-width: 1300px;
  margin: 0 auto;
  .red-container {
    position: relative;
    padding: 25px 50px;
    background-color: #4f748b;
    display: flex;
    justify-content: center;
    .right-image {
      position: absolute;
      margin-top: -25px;
      right: -18%;
      text-align: right;
      width: 40%;
      img {
        width: 100%;
      }
    }
    .title {
      text-align: left;
      color: #ededed;
      font-size: 2rem;
      padding-bottom: 40px;
    }
    //can be Commonly used for form fields
    .form {
      padding-bottom: 46px;
      textarea:focus,
      input:focus {
        outline: none;
      }
      .req-f {
        color: #ededed;
        text-align: end;
        top: 10px;
        font-size: 14px;
        font-weight: 500;
        position: relative;
      }
      input {
        height: 30px;
        display: block;
        margin: 10px 0;
        width: 100%;
      }
      textarea {
        width: 100%;
        height: 95px;
      }
    }
  }
  .map-address {
    display: flex;
    align-items: self-end;
    .map {
      margin-left: -3px;
      width: 45%;
      img {
        width: 100%;
      }
    }
    .address {
      margin-left: 60px;
      text-align: left;
      color: #892432;
      font-size: 30px;
      font-weight: 400;
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
.content {
  width: 50%;
}
// Copied overlay
.overlay {
  display: flex;
  background-color: #060f21;
  padding: 30px 12px;
  height: 20vh;
  justify-content: right;
  align-items: center;
  .title {
    margin: auto auto;
    color: #fff;
    font-size: 2rem;
  }
}
</style>
