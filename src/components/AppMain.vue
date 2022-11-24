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
                    <p class="icon-text">DIGITAL COMICS</p>
                </li>

                <li>
                    <img src="../img/buy-comics-merchandise.png" alt="DIGITAL">
                    <p class="icon-text">DC MERCHANDISE</p>
                </li>

                <li>
                    <img src="../img/buy-comics-subscriptions.png" alt="DIGITAL">
                    <p class="icon-text">SUBSCRIPTION</p>
                </li>

                <li>
                    <img src="../img/buy-comics-shop-locator.png" alt="DIGITAL">
                    <p class="icon-text">COMIC SHOP LOCATOR</p>
                </li>

                <li>
                    <img src="../img/buy-dc-power-visa.svg" alt="DIGITAL">
                    <p class="icon-text">DC POWER VISA</p>
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
  padding: 20px;
  
}

.icon-container{
    background-color: #0282f9;
    padding: 30px;
}

h1{
  color: white;
}

.icon-list{
    list-style: none;
}

li{
    display: flex;
    align-items: center;
    margin: auto;
    padding: 10px;
}

.icon-text{
    margin-left: 20px;
    color: white;
}

ul{
    display: flex;
    
}

img{
    width: 60px;
    height: 55px;
}

</style>