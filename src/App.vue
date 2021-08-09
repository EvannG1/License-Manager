<template>
  <div>
    <Navbar/>
    <Sidebar/>
    <router-view/>
    <Footer/>
  </div>
</template>

<script>
import './assets/scss/main.scss'
import Navbar from './components/Body/Navbar.vue'
import Sidebar from './components/Body/Sidebar.vue'
import Footer from './components/Body/Footer.vue'

export default {
  components: {
    Navbar,
    Sidebar,
    Footer
  }
}
</script>