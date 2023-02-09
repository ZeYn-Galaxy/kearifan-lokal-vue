<script>
import Home from './components/Home.vue'
import About from './components/About.vue'
import NotFound from './components/NotFound.vue'
import Navbar from './components/Navbar.vue'
import RumahAdat from './components/rumah-adat.vue'
import wisata from './components/wisata.vue'
import Suku from './components/suku.vue'
import makananKhas from './components/makanan-khas.vue'

const routes = {
  '/': Home,
  '/rumah-adat': RumahAdat,
  '/wisata': wisata,
  '/suku': Suku,
  '/makanan-khas': makananKhas
}

export default {
  data() {
    return {
      currentPath: window.location.hash
    }
  },
  computed: {
    currentView() {
      return routes[this.currentPath.slice(1) || '/'] || NotFound
    }
  },
  mounted() {
    window.addEventListener('hashchange', () => {
		  this.currentPath = window.location.hash
		})
  }
}
</script>

<template>
  <component :is="currentView" />
</template>
