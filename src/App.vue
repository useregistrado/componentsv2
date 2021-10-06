<template>
  <div id="app">
    <Navbar msg="Welcome to Your Vue.js App"/>
    <slider/>
    <services/>
    <contact/>
    <mision/>
    <footer2/>

  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import slider from './components/slider.vue'
import services from './components/services.vue'
import contact from './components/contact.vue'
import mision from './components/mision.vue'
import footer2 from './components/footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    slider,
    services,
    contact,
    mision,
    footer2
  }
}
</script>

