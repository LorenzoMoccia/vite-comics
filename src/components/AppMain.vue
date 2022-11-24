<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>


<template>
    <div class="container">
        <div class="content-container">
            <h1>--> Content goes here </h1>
        </div>
    
        <div class="icon-container">
            <ul class="icon-list">
                <li>
                    <img src="../img/buy-comics-digital-comics.png" alt="DIGITAL">
                </li>
            </ul>
        </div>
    
    </div>
</template>


<style lang="scss" scoped>

.container{
    display: flex;
    flex-direction: column;
}
.content-container{
  background-color: black;
  
}

.icon-container{
    background-color: #0282f9;

}

h1{
  color: white;
}

.icon-list{
    list-style: none;
}


</style>