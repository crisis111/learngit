<template>
  <div id="app">
    <img src="./assets/logo.png">
 <router-view></router-view>
		<router-link :to="{name:Hi,params:{username:'jspang'}}">hi页面</router-link>
		<router-link to="/hi/hi1">hi1页面</router-link>
		<router-link to="/hi/hi2">hi2页面</router-link>
 
  </div>
</template>

<script>
export default {
  name: 'App'
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
