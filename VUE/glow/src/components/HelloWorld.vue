<template>
  <body class="back-img">
    <!-- LANDING SECTION  -->
    <div class="landing-container">
      <section>
  <div class="margin"></div>
  <section>
    <h1 data-text="Welcome to my portfolio." class="text-light display-5 text-center fw-bold" id="h1"></h1>
    <div class="welcome-message"><span class="text-light display-2 text-center">I am an aspiring stack<br>stack developer.</span></div>
   </section>

   </section>
    </div>
    <!-- end of landing section -->
  </body>
</template>


<style scoped>

@import url('https://fonts.cdnfonts.com/css/aferd');  

*{
    font-family: 'aferd', sans-serif !important;                                             
}

body {
  min-height: 100vh;
}

.margin{
padding-top: 3rem;
}
.back-img{

    background-image: url("https://i.postimg.cc/tC0JMQrC/wallpaperflare-com-wallpaper-5.jpg");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    image-rendering: optimizeSpeed;
}


/* WELCOME MESSAGE */
.welcome-message {
    font-size: 80px;
    text-align: center;
    -webkit-animation: glow 1s ease-in-out infinite alternate;
    -moz-animation: glow 1s ease-in-out infinite alternate ;
    animation: glow 1s ease-in-out infinite alternate ;
  }
 @keyframes glow {
    from {
      text-shadow: 0 0 20px #c017a9, 0 0 30px #470dce, 0 0 40px #f900c7, 0 0 50px;
    }
    to {
      text-shadow: 0 0 20px #2b04b7e1, 0 0 30px #ff4da6, 0 0 40px #9a07df,
        0 0 50px #ff4da6 ;
    }
  }

/* NEON FONT */
:root {
    --var-color: rgb(12, 38, 236);
  }
  section {
    width: 100%;
  }
  #h1 {
    font-size: 30px;
    color: var(--var-color);
    position: relative;
  }
  #h1::before {
    content: attr(data-text);
    text-shadow: 0px 0px 20px var(--var-color);
    filter: blur(0px) brightness(0);
    animation: flicker 2s linear forwards;
    animation-delay: 0.2s;
  }
  @keyframes flicker {
    0% {
      filter: blur(0px) brightness(1);
    }
    3% {
      filter: blur(0px) brightness(0);
    }
    6% {
      filter: blur(0px) brightness(0);
    }
    7% {
      filter: blur(0px) brightness(1);
    }
    8% {
      filter: blur(0px) brightness(0);
    }
    9% {
      filter: blur(0px) brightness(1);
    }
    10% {
      filter: blur(0px) brightness(0);
    }
    20% {
      filter: blur(0px) brightness(1);
    }
    50% {
      filter: blur(0px) brightness(1);
    }
    99% {
      filter: blur(0px) brightness(0);
    }
    100% {
      filter: blur(0px) brightness(1);
    }
  }

.margin {
  padding-top: 6rem;
}

@media only screen and (max-width:300px){
  h1{
    font-size:small !important;
  }
}

</style>


<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>


