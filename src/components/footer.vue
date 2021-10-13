<!-- Common Footer for pages -->
<template>
  <div class="base-line">Experienced and Local Attorneys Here for You</div>
  <div class="footer-content">
    <div class="office">
      <div class="title">OFFICE</div>
      <p>105 Tivoli Street</p>
      <p>Abbeville, LA</p>
      <p>337-893-3423</p>
    </div>
    <div class="contract">
      <div class="title">CONTRACT</div>
      <p class="disclaimer">Disclaimer</p>
      <p class="disclaimer">Sitemap</p>
      <p class="disclaimer">Privacy policy</p>
    </div>
    <div class="privacy-policy">
      <div class="title">PRIVACY POLICY</div>
      <p class="policy">
        Privacy Policy Purpose Federal and state laws and regulations require
        Gabe A. Duhon, L.L.C. (“the Company”) to disclose how it collects,
        shares, and protects any personal information obtained during the course
        of normal business operations. This Privacy Policy and Notice is to be
        distributed pursuant to Title V of the Gramm-Leach-Bliley Act (GLBA).
        Any information collected will only be used in accordance with this
        privacy statement.
      </p>
    </div>
  </div>
  <div class="schedule-btn">
    <button class="button">SCHEDULE A CONSULTATION</button>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style lang="scss" scoped>
.base-line {
  margin-top: 120px;
  color: #4f748b;
  font-size: 28px;
}
.footer-content {
  margin-top: 52px;
  padding: 0 120px;
  justify-content: end;
  display: flex;
  font-size: 12px;
  p {
    margin: 5px 0;
  }
  div {
    margin: 0 22.5px;
  }
  .title {
    margin: 0 auto;
    color: #707070;
  }
  .office {
    text-align: left;
  }
  .contract {
    text-align: left;
  }
  .privacy-policy {
    text-align: justify;
    width: 210px;
  }
}
.schedule-btn {
  width: 600px;
  height: 65px;
  padding: 0 70px;
  button {
    background-color: #ededed;
    width: 565px;
    height: 55px;
    border: none;
    color: #892432;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
  }
}
</style>
