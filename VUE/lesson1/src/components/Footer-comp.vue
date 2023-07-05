<template>
    <div class="footer">
        <h6>Feet</h6>
        <p class="footer-text-left">
<routerlink class="menu" to="/">Home</routerlink>
<routerlink class="menu" to="/">Tutorial</routerlink>
<routerlink class="menu" to="/">About</routerlink>
        </p>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.footer {
    position: fixed;
    bottom: 0;
    left: 0; 
    
    height: 90px;
    background-color: chocolate;
}

.footer-text-left{
    font-size: 25px;
    padding: 40px;
    float: left;
    word-spacing: 20px;
}

.menu:hover {
    background-color: yellowgreen;
    font-size: 20px;
}
</style>