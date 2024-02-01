<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <LoginForm/>
</template>

<script>
import LoginForm from './components/LoginForm.vue'

export default {
  name: 'App',
  components: {
    LoginForm
  }
}
</script>

<style>
  @import './assets/base.css';
</style>
