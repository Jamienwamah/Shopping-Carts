<template>
  <div class="card">
    <h3>{{ product.name }}}</h3>

    <h5 class="price">Price: ${{ product.price.toFixed(2) }}}</h5>
  </div>
</template>

<script>
export default {
  props: ["products"]
};
</script>

<style scoped></style>
