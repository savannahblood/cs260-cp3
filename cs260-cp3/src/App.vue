<template>
  <div id="app">
    <header>
      <router-link to="/">
        <div id='logo'>
          <img src="./assets/images/logo.png">
        </div>
      </router-link>
      <a id='hamburger' data-toggle="collapse" href="#header-nav" role="button" aria-expanded="false" aria-controls="collapseExample">
        <div class='line' id='one'></div>
        <div class='line' id='two'></div>
        <div class='line' id='three'></div>
      </a>
      <nav id='header-nav' class='collapse'>
        <ul>
          <router-link to="/pricing">
            <li class="menu-item pricing"><a href="#">Pricing</a></li>
          </router-link>
          <router-link to="/holidays">
            <li class="menu-item holidays"><a href="#">Holidays</a></li>
          </router-link>
          <router-link to="/signup">
            <li class="menu-item signup"><a href="#">Sign Up</a></li>
          </router-link>
          <router-link to="/login">
            <li class="menu-item login"><a href="#">Log In</a></li>
          </router-link>
        </ul>
      </nav>
    </header>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
</style>
