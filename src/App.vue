<template>
  <Header :header_categories="['Accueil', 'Projet', 'Contact']"/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Simon Cocchi Website"/>
  <div class="justify-center flex bg-yellow-300 items-center h-screen">
    <div class="text-4xl">
      Hello 👋🏼
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from "@/components/Header";

export default {
  name: 'App',
  components: {
    Header,
    HelloWorld
  }
}
</script>

<style>
#app {
}
</style>
