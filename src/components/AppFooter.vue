<script>
export default {
  data() {
    return {
      
    }
  }
}
</script>

<template>
    <div class="container-footer">
        <div class="first-col">
            <ul>
                <li><h1>DC COMICS</h1></li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
            </ul>

            <ul>
                <li><h1>SHOP</h1></li>
                <li>Testo</li>
                <li>Testo</li>
            </ul>
        </div>


        <div class="second-col">
            <ul>
                <li><h1>DC</h1></li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
            </ul>
        </div>

        <div class="tirdh-col">
            <ul>
                <li><h1>SITES</h1></li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
                <li>Testo</li>
            </ul>
        </div>
        
        <img src="../img/dc-logo-bg.png" alt="" class="dc-logo">
    </div>
</template>

<style lang="scss" scoped>

ul{
    list-style: none;
}

.container-footer{
    display: flex;
    background: url('../img/footer-bg.jpg');
}

h1{
    color: white;
}

li{
    color: #887a7c;
    padding: 3px;
}
.dc-logo{
    height: 380px;
    margin-left: 800px;
}
</style>