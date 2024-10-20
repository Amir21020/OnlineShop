<script setup>
  defineProps({
    title: String,
    price: Number
  })

</script>


<template>
  <div class="product">
    <h2>Товар: Кроссовки Nike</h2>
    <h3>Цена: 15000</h3>
  </div>
</template>


<style scoped>
  .product{
    border: 1px solid blue;
    padding: 10px;
    margin-bottom: 10px;
  }
</style>
