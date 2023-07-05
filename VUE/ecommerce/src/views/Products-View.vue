
<template>
    <div class="products">
        <h1>Products page</h1>
    </div>
    <ProductComp/>
  </template>

  <script>
import ProductComp from '@/components/Product-Card-Comp.vue';

export default {
    components: {ProductComp},
};

</script>