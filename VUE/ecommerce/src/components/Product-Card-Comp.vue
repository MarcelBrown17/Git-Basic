<template>
<body>
     <router-link :to="{ name: 'Products', params: { id: products.id } }">
        <!-- How products will be displayed from array. -->
        <div class="item">
                <div class="item-container" v-if="product" :key="products.ID">
                    <div class="item-img" >
                        <img src="{{products.imgSrc}}" alt="products.name">
                    </div>
                    <div class="desc">
                        <h3>{{products.name}}</h3>
                        <h2>R{{products.price}}"</h2>
                        <p>
                            {{products.description}}
                        </p>
                    </div>
                    <div class="add-to-cart" @click="addToCart" key="{{products.id}}">
                        <button class="add-to-cart">Add to cart</button>
                    </div>
                </div>
            </div>
    </router-link> 
    </body>
</template>

<script>
export default {
    data(){
        return{
            data:[],
            
        }
    },
    methods: {
async Data(){
    const res = await fetch ('https://marcelbrown17.github.io/vue-prod/database.json')
                let parsedData = await res.json()
                this.data = parsedData.products;
},
    },
    mounted(){
        this.fetchData
    },

};

</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Lato:ital@1&family=Raleway&display=swap');

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html{
  overflow-x: hidden !important;
}

body{
background-color: #c6c6c6 !important;
font-family: 'Lato', sans-serif !important;
font-family: 'Raleway', sans-serif !important;
}

.container{
  margin: auto;
}

.heading{
  margin-top: 30px;
  font-size: 5rem;
  color: #000;
}

.card{
    background-color: black;
}
/* PRODUCTS */
.products-container {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content:center;
    align-items: center;
  }

  /* products list */
  .products-list {
    width: 100%;
    padding-top: 20px;
    margin-bottom: 2rem;
 margin: auto;
  }
  
  /* PRODUCTS */
  .products {
    height: 100%;
    width: 100%;
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: repeat(3, 3fr);
    margin: auto;
  }
  .products img {
    width: 210px;
    height: 270px;
  }
  .products .item {
    display: flex;
    align-items: center;
    justify-content: center !important;
    flex-direction: column;
    width: 100%;
    margin-top: 20px;
  }
  .products .item .item-container {
    width: 250px;
    background-color: #000;
    border-radius: 25px;
    position: relative;
  }
  .products .item .item-container .item-img {
    width: 100%;
    height: 300px;
    background-color: white;
    border: 1px solid #000;
    border-radius: 25px 25px 0 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .products .item .item-container .desc {
    width: 100%;
    color: #fff;
  
    padding: 10px;
  }
  .products .item .item-container .add-to-cart {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 8px;
    margin-bottom: 10px;
    cursor: pointer;
    border-radius: 15px;

  }
  
  footer{
margin-top: 5rem;
  }


  @media only screen and (max-width:300px) {
    html,body {
        margin: 0;
        padding: 0;
        width: 100%;
        height: 100%;
        overflow-x: hidden;
    }
    .products{
      display: grid;
      grid-template-columns: repeat(1, 3fr) !important;

      width: 250px;
    }
    footer{
      margin-top: 5rem;
    }
    .cart {
      display: flex;
      flex-direction: column;
      width: 100px;
    background-color: #29acd4;
      margin-top: 5rem;
      width: 100%;
    }
    .cart-item{
      display: flex;
      flex-direction: column;
    }
  }

  .item{
    margin-bottom:10px;
  }


</style>