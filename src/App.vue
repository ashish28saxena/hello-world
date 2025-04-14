<template>
  
  
  <HomePage></HomePage>
  <LoginPage></LoginPage>
  <RegistrationPage></RegistrationPage>
</template>

<script>

import HomePage from './components/HomePage.vue'
import LoginPage from './components/LoginPage.vue'
import RegistrationPage  from './components/RegistrationPage.vue'
export default {
  name: 'App',
  components: {
    HomePage,
    LoginPage,
    RegistrationPage,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
