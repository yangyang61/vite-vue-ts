<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <br />
  <router-link to="/">home</router-link>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <router-link to="/vuex">vuex</router-link>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <router-link to="/axios">axios</router-link>
  <router-view></router-view>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
})
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
