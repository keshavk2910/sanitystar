<template>
  <div class="overlay">
    <div class="title">Contact Us</div>
  </div>
  <div class="main-container">
    <div class="red-container">
      <div class="content">
        <div class="right-image">
          <img src="../assets/consulting.png" alt="consult" />
        </div>
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
    <div class="description">
      Suspendisse dignissim ultrices dolor, quis condimentum orci. Proin eu
      pulvinar leo. Quisque tempor aliquet convallis. Ut in urna lacinia,
      viverra ex quis, suscipit sapien. Donec sed ipsum velit. Praesent at
      faucibus purus. Curabitur pretium nibh vel nisi efficitur viverra. Nullam
      finibus in lectus ut fermentum. Phasellus hendrerit nec nulla a posuere.
      Fusce rhoncus ut sem et lobortis. Aenean tempus ut neque eu eleifend.
      Curabitur quis urna mi. Suspendisse odio justo, lobortis vel auctor ut,
      ornare eget tortor.
    </div>
  </div>
</template>

<style scoped lang="scss">
// Common header for other than home
.main-container {
  // common page layout
  box-sizing: border-box;
  padding: 0 120px;
  .red-container {
    padding: 25px 175px;
    background-color: #892432;
    display: flex;
    .right-image {
      position: absolute;
      margin-top: -25px;
      right: -3%;
      img {
        height: 320px;
        width: 420px;
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
        width: 485px;
        height: 30px;
        display: block;
        margin: 10px 0;
      }
      textarea {
        width: 485px;
        height: 95px;
      }
    }
  }
  .map-address {
    display: flex;
    align-items: self-end;
    .map {
      margin-left: -3px;
      img {
        width: 400px;
        height: 240px;
      }
    }
    .address {
      margin-left: 50px;
      text-align: left;
      color: #892432;
      font-size: 18px;
      font-weight: 600;
    }
  }
  .description {
    margin: 85px 0 0 auto;
    width: 495px;
    text-align: justify;
  }
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
