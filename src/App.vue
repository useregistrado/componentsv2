<template>
  <div id="app">
    <Navbar msg="Welcome to Your Vue.js App"/>
    <slider/>
    <services/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import slider from './components/slider.vue'
import services from './components/services.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    slider,
    services
  }
}
</script>

