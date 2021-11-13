<script>
  import Data from "../data"
	export default {
		name : "Navbar",
    data(){
      return {
        data : Data
      }
    }
	}
</script>
<template>
<nav class="navbar is-white is-fixed-top" style="padding: 5px">
  <div class="navbar-brand">
    <router-link class="navbar-item" to="/">
      <h1 style="color: #042454; font-size: 20px"><b>Growth Academy</b></h1>
    </router-link>
    <div class="navbar-burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>
   <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        Videos
      </a>

      <a class="navbar-item">
        Podcast
      </a>

        <a class="navbar-item">
          Blog
        </a>
    </div>
  </div>
      <div class="navbar-end">
      <div class="navbar-item">
        <div class="field is-grouped">
          <p class="control">
            <a style="color: #042454" class="bd-tw-button button" target="_blank" href="https://www.facebook.com/Webinium-103348078810128/" >
              <span class="icon">
                <i class="fab fa-facebook"></i>
              </span>
            </a>
          </p>
          <p class="control">
            <a style="background: #042454;" class="button is-primary" href="https://www.instagram.com/webinium352/" target="__blank">
              <span class="icon">
                <i class="fab fa-instagram"></i>
              </span>
            </a>
          </p>
        </div>
      </div>
    </div>
</nav>      
</template>
<style scoped>
	a:hover{
		color: #042454;
	}


</style>