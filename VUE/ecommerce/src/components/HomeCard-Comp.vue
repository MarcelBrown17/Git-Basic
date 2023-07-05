<template>
    <!-- Cards -->

    <section class="skate-aesthetic">
      <div class="cards">
        <div class="card1">
          <div class="card-content-1">
            <h3 class="h-3">Explore</h3>
          </div>
        </div>
        <div class="card2">
          <div class="card-content-2">
            <h3 class="h-3">Master</h3>
          </div>
        </div>
        <div class="card3">
          <div class="card-content-3">
            <h3 class="h-3">Become<br />Phenomenal</h3>
          </div>
        </div>
      </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.skateaesthetic{
    padding: 0;
}
.card1{
    background-image: url(https://i.postimg.cc/K85JRKzQ/skater-boy-in-style-iumzy5wkdl11pqsf.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    width: 100%;
    height: 520px !important;
    color: white;
}
.card2{
    background-image: url(https://i.postimg.cc/TPbRmTL5/action-active-activity-fun.jpg);
    background-position: center;
    width: 100%;
    height: 520px !important;
    color: white;
}
.card3{
    background-image: url(https://i.postimg.cc/6py6WrB0/sports-skateboarding-wallpaper-preview.jpg) !important;
    width: 100%;
    height: 520px !important;
    color: white;
    background-position: center;
}
.cards {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}

.card-content-1{
    display: grid;
    text-align: right;
    margin-top: 4rem;
    margin-right: 3rem;
    color: rgb(4, 153, 153) !important;
    font-weight: bold !important;
}
.card-content-2{
    display: grid;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-top: 1rem;
    color: #c6c6c6 !important;
}
.card-content-3{
    display: grid;
    justify-content: center;
    align-items: center;
    text-align: center;
    margin-top: 20rem;
    font-weight: bold;
    color: rgb(255, 255, 255) !important;
        font-weight: bold !important;
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
            .cards{
                display: flex;
                flex-direction: column;
            }
}
</style>