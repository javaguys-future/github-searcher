<template>
  <div id="app">
    <header>
      <router-link to="/">
          <div class="logo">
              <img src="https://cdn0.iconfinder.com/data/icons/octicons/2857/logo-github-512.png" alt="">
          </div>
      </router-link>
      <search></search>
    </header>
    <router-view></router-view>
    <footer class="app-footer">
      <p>&copy; Copyright 2018 Made with <i class="fa fa-heart"></i> by Mr. CaT</p>
    </footer>
  </div>
</template>

<script>
import Search from './components/Search.vue'
import Repositories from './components/Repositories.vue'

export default {
  name: 'app',
  components: { Search, Repositories }
}
</script>

<style src="./assets/main.css">
</style>
