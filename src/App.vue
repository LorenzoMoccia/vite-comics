<script>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import AppHeader from './components/AppHeader.vue'



export default {
  components: {
    AppHeader
    
  }
}

</script>

<template>
  <header class="debug">
    <AppHeader/>
    
    
  </header>
  
    

</template>

<style scoped>
.debug{
  border: 1px dashed black;
}

.logo{
  max-width: fit-content;
  border-radius: 50%;
}
</style>
