<template>
  <div class="productsComp">
    <h1>{{ product_name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'ProductsComp',
  props: {
    product_name: String
  }
}
</script>
