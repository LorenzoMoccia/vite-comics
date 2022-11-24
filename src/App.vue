<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'



export default {
  components: {
    AppHeader,
    AppMain
    
  }
}

</script>

<template>
  <header>
    <AppHeader/>
  </header>
  <main class="debug">
    <AppMain/>
  </main>
  
    

</template>

<style scoped>
.debug{
  border: 1px dashed black;
}


</style>
