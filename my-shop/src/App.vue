<template>
  <div id="app">
    <ProductCard
      name="Українська вишиванка"
      description="Стильна вишиванка з традиційними орнаментами."
      price="1500"
      image="https://upload.wikimedia.org/wikipedia/commons/7/75/Folklore_of_Sanok%2C_2010_1.JPG"
    />
  </div>
</template>

<script>
import ProductCard from './components/ProductDard.vue';
export default {
  name: 'App',
  components: {
    ProductCard
  }
}
</script>

<style>

</style>
