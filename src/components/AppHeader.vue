<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <div class="header-container">
    <div class="container-logo">
      <img src="../img/dc-logo.png" alt="Logo">
    </div>

    <div class="container-navbar">
      <ul class="navbar-list">
        <li>CHARACTERS</li>
        <li>COMICS</li>
        <li>MOVIES</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>COLLECTIBLES</li>
        <li>VIDEOS</li>
        <li>FANS</li>
        <li>NEWS</li>
        <li>SHOP</li>
      </ul>
    </div>
  </div>
  
</template>

<style lang="scss" scoped>
.header-container{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

li{
  display: inline-block;
  padding: 5px;
}
.container-navbar{
  display: flex;
}
.navbar-list{
  list-style: none;
}


</style>