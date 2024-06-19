<script setup lang="ts">
import ItemListing from './ItemListing.vue';
import Nav_Bar from './Nav_Bar.vue';
</script>

<template>
  <div class="Flex">
    <Nav_Bar />
    <ItemListing />
  </div>
</template>

<style scoped>
.Flex
{
  display: flex;
  height: 100%;
  width: 100%;
}
</style>
