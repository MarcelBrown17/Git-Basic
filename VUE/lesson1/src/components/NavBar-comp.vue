 <template>
 <nav class="topnav">
    <router-link  class="active" to="/">Home</router-link> |
    <router-link to="/tutorial">Tutorial</router-link> | 
    <router-link to="/about">About</router-link>
  </nav>
 </template>
 
    

  <script>
export default{

}
</script>

<style scoped>

.topnav{
background-color:black;
overflow:hidden;
}

routerlink {
  float:left;
  color:white;
  text-align:center;
  padding:4px 16px;
  text-decoration:none;
  font-size:17px;
}
</style>