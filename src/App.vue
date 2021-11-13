<script>
  import Data from "./data"
  import Navbar from "./components/Navbar.vue"
import Cards from "./components/Cards.vue";
import Footer from "./components/Footer.vue";

  export default {
    data() {
        return {
            data: Data
        };
    },
    components: { Navbar, Cards, Footer }
}
</script>

<template>
  <Navbar/>
  <h1 style="text-align: center; margin-top:100px; padding: 30px" class="title">Welcome to <span style="color: #FCA909">Growth Academy</span></h1>
  <div class="image-container">
    <img src="/logo.png" class="main-image" />
  </div>
  <div class="keep-center">
  <div class="card">
  <div class="card-content">
    <p class="title">
      Get a copy of my book Boundry Loop
    </p>
    <p class="subtitle">
      Saurav Adhikari
    </p>
  </div>
  <footer class="card-footer">
    <p class="card-footer-item">
      <span>
        View on <a href="">Daraz</a>
      </span>
    </p>

  </footer>
</div>
</div>
  <Cards/>
  <Footer/>
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.main-image{
  height: 500px;
}
.image-container{
  display: flex;
  justify-content: center;
}

.keep-center{
  display: flex;
  justify-content: center;
  margin: 50px;
}
</style>
