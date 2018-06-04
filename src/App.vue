<template>
  <div id="app">
<!-- <app-user></app-user> -->
<div>
  <router-link to="/">HOME</router-link>
  <router-link to="/blog">BLOG</router-link>
  <router-link to="/account">ACCOUNT</router-link>
</div>
<router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">

</style>
