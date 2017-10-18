<template>
  <div id="app">
    <router-link to="/">/hello</router-link>
    <router-link to="/home">/home</router-link>
    <keep-alive include="Hello">
      <router-view></router-view>
    </keep-alive>
  </div>
</template>
<script>

export default {
  name: 'app',
  data() {
    return {
    }
  },
  created() {
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
