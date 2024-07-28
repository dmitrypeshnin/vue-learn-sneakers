<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      image-url="/sneakers/sneakers-2.jpg"
      title="Мужские Кроссовки Nike Blazer Mid Suede"
      :price="12500"
    />
    <Card image-url="/sneakers/sneakers-3.jpg" />
    <Card image-url="/sneakers/sneakers-4.jpg" />
    <Card image-url="/sneakers/sneakers-5.jpg" />
    <Card image-url="/sneakers/sneakers-6.jpg" />
    <Card image-url="/sneakers/sneakers-7.jpg" />
    <Card image-url="/sneakers/sneakers-8.jpg" />
    <Card image-url="/sneakers/sneakers-9.jpg" />
    <Card image-url="/sneakers/sneakers-10.jpg" />
    <Card image-url="/sneakers/sneakers-11.jpg" />
    <Card image-url="/sneakers/sneakers-12.jpg" />
  </div>
</template>

<script setup>
  import Card from './Card.vue'
</script>
