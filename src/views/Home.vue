<template>
  <div class="home">
    <!--
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    -->
    <Adressd/>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import Adressd from '@/components/Adress.vue'

export default {
  name: 'Home',
  components: {
    //HelloWorld,
    Adressd
  }
}
</script>
