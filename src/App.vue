<template>
  <div id="app">
    <Navbar msg="Welcome to Your Vue.js App"/>
    <slider/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import slider from './components/slider.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    slider
  }
}
</script>

