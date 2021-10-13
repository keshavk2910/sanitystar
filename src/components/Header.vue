<template>
  <header>
    <div class="headMain">
      <div class="logoSide">
        <router-link to="/"
          ><img alt="Vue logo" src="../assets/logo.png"
        /></router-link>
      </div>
      <div class="menuSide">
        <div class="navTop">
          <nav>
            <ul>
              <li><router-link to="/">Home</router-link></li>
              <li><router-link to="/about">About</router-link></li>
              <li><router-link to="/resources">Resources</router-link></li>
              <li><router-link to="/faq">FAQ</router-link></li>
              <li><router-link to="/contact">Contact</router-link></li>
            </ul>
          </nav>
        </div>
        <div class="navBottom">
          <div class="colorOne">
            <button>Real Estate</button
            ><a class="phone" href="tel:2222222222">2222222222</a>
          </div>
          <div class="colorTwo">
            <p>ATTORNEYS AT LAW</p>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style scoped lang="scss">
.headMain {
  display: flex;
  justify-content: end;
  align-items: center;
}
.logoSide {
  width: 20%;
}
.menuSide {
  width: 70%;
}
ul {
  list-style: none;
  li {
    display: inline-block;
    padding: 5px 15px;
  }
}
</style>
