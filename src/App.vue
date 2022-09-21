<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <FirstComponent username="huy8895"></FirstComponent>
  <SecondComponent></SecondComponent>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FirstComponent from "@/components/FirstComponent";
import SecondComponent from "@/components/SecondComponent";

export default {
  name: 'App',
  components: {
    SecondComponent,
    FirstComponent,
    HelloWorld
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
