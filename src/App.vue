<template>
  <Header />
  <router-view />
  <Footer />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  margin: 0;
}
#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
img {
  max-width: 100%;
  max-height: 100%;
}
button {
  cursor: pointer;
}
</style>
<script>
// @ is an alias to /src
import Header from './components/Header.vue'
import Footer from './components/footer.vue'
export default {
  components: {
    Header,
    Footer
  }
}
</script>
