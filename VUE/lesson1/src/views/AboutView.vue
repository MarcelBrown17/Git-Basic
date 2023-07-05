<template>
  <div class="about">
 <!-- <h2>Text Input</h2>
   <input v-model="text">{{text}}
   <h2>Checkbox</h2>
   <input v-model="checked" id="checkbox" type="checkbox">{{checkbox}}
   <label for="checkbox">Checked:{{checked}}</label> -->

   <h2>Multi Checkbox</h2>
<input type="checkbox" id="Cheslyn" v-model="checkName">
<label for="Cheslyn">Cheslyn</label>
<input type="checkbox" id="Luke" v-model="checkedNames">
<label for="Luke">Luke</label>
<p>Checked:
    <pre>{{ checkedNames }}</pre>
</p>

  </div>
</template>

<script>

// export default{
// data(){
//     return{
//         text:'',
//         checked:'true',
//     }
// }
// }

export default{
 data(checkedNames){
    return{
        Text:'',
        checked: 'true',
checkedNames:['Cheslyn'],
    }
 }
}

</script>