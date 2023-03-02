<!-- eslint-disable vue/multi-word-component-names -->
<script setup>
const checkout = () => {
  alert("Cheking out items");
};
</script>
<template>
  <div>
    <h1 class="text-4xl">Home</h1>
    <button @click="checkout">Checkout</button>
  </div>
</template>

<style module></style>
