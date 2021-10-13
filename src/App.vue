<template>
  <div id="app">
    <Header /> 
    <cart />
    <signup />
    <images />
    <phone />
    <affordable />
    <learn />
    <newsletter />
    <last-component />
    
  </div>
</template>

<script>

import Header from './components/Header.vue'
import Cart from './components/Cart.vue'
import Signup from './components/Signup.vue'
import Images from './components/Images.vue'
import Phone from './components/Phone.vue'
import Affordable from './components/Affordable.vue'
import Learn from './components/Learn.vue'
import Newsletter from './components/Newsletter.vue'
import LastComponent from './components/LastComponent.vue'





export default {
  name: 'App',
  components: {
    Header,
    Cart,
    Signup,
    Images,
    Phone,
    Affordable,
    Learn,
    Newsletter,
    LastComponent
  }
}
</script>

