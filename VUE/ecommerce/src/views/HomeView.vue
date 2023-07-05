<template>
 <CarouselComp/>
 <HomeCard-Comp/>
</template>

<script>
import CarouselComp from '@/components/Carousel-Comp.vue';
import HomeCardComp from '@/components/HomeCard-Comp.vue';

export default {

  components: {
    CarouselComp,
    HomeCardComp
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Lato:ital@1&family=Raleway&display=swap');


*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    text-decoration: none !important;
    
}

body{
    background-color: rgb(28, 26, 26);
    min-height: 100vh;
    font-family: 'Lato', sans-serif !important;
    font-family: 'Raleway', sans-serif !important;
}

@media only screen and (max-width:300px) {
    html,body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        overflow-x: hidden;
    }
    
h3{
    font-size: medium;
}

    .carousel-section img{
width: 100% !important;
height: 15rem !important;
    }
    .slogan-1{
        font-size: 40px !important
    }
    
}


@media only screen and (max-width:700px) {
    html,body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        overflow-x: hidden;
    }
}
</style>
