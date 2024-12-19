<template>
  <h2>Product</h2>
</template>

<script setup lang="ts">
import { useRoute } from 'vue-router'

const route = useRoute()
console.log(route.params)
</script>

<style lang="scss" scoped>
</style>
