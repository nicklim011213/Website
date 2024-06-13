<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import ItemListing from './components/ItemListing.vue'
</script>

<template>
  <div class="GradWrap">
    <header>
      <div class="wrapper">
        <HelloWorld msg="Resume / Projects Site" />
      </div>
    </header>
  </div>
  <div class = "Items">
      <ItemListing />
    </div>
</template>

<style scoped>
header {
  line-height: 1.5;
  place-items: center;
  margin: 0 auto;
  height: 15vh;
}

html
{
  height: 100vh;
}

.Items
{
  height: 85vh;
  background-color: #ffDead;
}

.GradWrap
{
  background: rgb(255,222,173);
  background: linear-gradient(0deg, rgba(255,222,173,1) 0%, rgba(64,199,2,1) 100%);
}
</style>
