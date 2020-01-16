<template>
  <div id="products-page">
    <CardProduct/>
  </div>
</template>

<script>

import CardProduct from '../components/card-product/card-product.vue'

export default {
  name: 'ProductsPage',
  components : {
    CardProduct
  }
}
</script>

