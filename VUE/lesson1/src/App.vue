<template>
<NavBarComp/>
<FooterComp/>
<FormComp/>
  <router-view/>
</template>
<script>

 import NavBarComp from './components/NavBar-comp.vue'
 import FooterComp from './components/Footer-comp.vue'
 import FormComp from './components/Form-comp.vue'
  
export default {

components: {NavBarComp, FooterComp, FormComp}

}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
red{color:red}
</style>
