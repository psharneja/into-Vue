<template>
<div id="user">
<h3>The username is  {{username}}</h3>
<app-info></app-info>
</div>

</template>
<script>
  import Info from './Info.vue';

export default {
data() {
  return {
    username: 'Max'
  }
},
components: {
  'app-info': Info
}
}
</script>
<style scoped>
h3 {
  font-variant: small-caps;
}
</style>
