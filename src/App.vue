<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <p><router-link :to="{name: 'home'}">home-page</router-link></p>
    <p><router-link :to="{name: 'about'}">about-page</router-link></p>
    <router-view/>
  </div>
</template>

<script lang="ts">
import { Vue } from 'vue-property-decorator';

export default class App extends Vue {}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
