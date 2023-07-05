<template>
        <!-- Landing Page -->
        <section class="carousel-section">
      <!-- Carousel wrapper -->
      <div
        id="carouselMaterialStyle"
        class="carousel slide carousel-fade"
        data-mdb-ride="carousel"
      >
        <!-- Indicators -->
        <div class="carousel-indicators">
          <button
            type="button"
            data-mdb-target="#carouselMaterialStyle"
            data-mdb-slide-to="0"
            class="active"
            aria-current="true"
            aria-label="Slide 1"
          ></button>
          <button
            type="button"
            data-mdb-target="#carouselMaterialStyle"
            data-mdb-slide-to="1"
            aria-label="Slide 2"
          ></button>
          <button
            type="button"
            data-mdb-target="#carouselMaterialStyle"
            data-mdb-slide-to="2"
            aria-label="Slide 3"
          ></button>
        </div>

        <!-- Inner -->
        <div class="carousel-inner shadow-4-strong">
          <!-- Single item -->
          <div class="carousel-item active">
            <img
              src="https://i.postimg.cc/fy6vjsXR/523893.jpg
        "
              class="d-block w-100"
              alt="Sunset Over the City"
            />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="slogan-1">Dont H8 Sk8</h2>
            </div>
          </div>

          <!-- Single item -->
          <div class="carousel-item">
            <img
              src="https://i.postimg.cc/GpcTQ2rt/photo-1520045892732-304bc3ac5d8e.jpg"
              class="d-block w-100"
              alt="Canyon at Nigh"
            />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="slogan-2">When I Get Board I Skate</h2>
            </div>
          </div>

          <!-- Single item -->
          <div class="carousel-item">
            <img
              src="https://i.postimg.cc/FzZQPrpZ/f5511a1fe1a2de9ed31f61d380b048db.jpg"
              class="d-block w-100"
              alt="Cliff Above a Stormy Sea"
            />
            <div class="carousel-caption d-none d-md-block">
              <h2 class="slogan-3">Master Your Craft</h2>
            </div>
          </div>
        </div>
        <!-- Inner -->

        <!-- Controls -->
        <button
          class="carousel-control-prev"
          type="button"
          data-mdb-target="#carouselMaterialStyle"
          data-mdb-slide="prev"
        >
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button
          class="carousel-control-next"
          type="button"
          data-mdb-target="#carouselMaterialStyle"
          data-mdb-slide="next"
        >
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
      <!-- Carousel wrapper -->
    </section>

    
</template>

<script>
export default {

}
</script>

<style>
h3{
    font-weight: bold !important;
    font-size: 50px !important;
}

.carousel-section img{
    height: 37rem !important;
}


.slogan-1{
margin-bottom: 19rem !important;
font-size: 100px !important;
text-shadow: 6px 6px #000000;
}
.slogan-2{
margin-bottom: 3rem;
font-size: 100px !important;
text-shadow: 6px 6px #000000;
}
.slogan-3{
margin-bottom: 25rem;
font-size: 100px !important;
text-shadow: 6px 6px #000000;
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
    .carousel-section img{
        width: 100% !important;
        height: 20rem !important;
            }
    .carousel-section img:hover{
        
            }
            .cards{
                display: flex;
                flex-direction: column;
            }
}
</style>