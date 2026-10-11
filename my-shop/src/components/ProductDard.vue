<template>
    <div class="product-card.">
        <img class="product-image" :src="image" :alt="name">
        <h2>{{ name }}</h2>
        <p>{{ description }}</p>
        <p class="price">{{ price }}</p>
        <button class="buy-button">Купити</button>
    </div>
</template>

<script>
    export default{
        props:{
            name:String,
            description:String,
            price:Number,
            image:String
        }
    }
</script>

<style scoped>
</style>