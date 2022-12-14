<template>
  <NavBar/>

  <About></About>
  </template>

<script>
import NavBar from '@/components/NavBar.vue'
import About from '@/components/About.vue'

export default {
  name: 'HomeView',
  components: {
    NavBar,About
  }
}

</script>

<style>

</style>