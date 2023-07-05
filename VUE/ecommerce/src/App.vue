<template>
 <NavBarComp/>
  <router-view/>
  <Product-Card-Comp/>
  <FooterComp/>
<head>
     <!-- Font Awesome -->
     <link
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css"
      rel="stylesheet"
    />
</head>
  <body>
 
  </body>
   
</template>
<script>

import FooterComp from './components/Footer-Comp.vue';
import NavBarComp from './components/NavBar-Comp.vue';
export default {
components: {NavBarComp, FooterComp}
}

</script>

<style>

</style>
