<template>
  <div class="products">
    <h1>Liste des produits</h1>
  </div>
    <ProductsComp product_name={{ $route.params.product_id }}/>
</template>

<script>
// @ is an alias to /src
import ProductsComp from '@/components/ProductsComp.vue'

export default {
  name: 'Products',
  components: {
    ProductsComp
  }
}
</script>
