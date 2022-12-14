<template>
<NavBar></NavBar>
 <Products></Products>
 <footer/>


</template>

<script>


import NavBar from '@/components/NavBar.vue'
import Products from '@/components/Products.vue'
import Footer from '@/components/Footer.vue'



export default {
  name: 'HomeView',
  components: {
    NavBar,Products,Footer
  }
}

</script>