<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router';
import HelloWorld from './components/HelloWorld.vue';
import BodyComp from './components/BodyComp.vue';
</script>

<template>
    <header>
        <HelloWorld msg="Resume / Projects Site" />
    </header>
    <BodyComp />
</template>

<style scoped>
header {
  line-height: 1.5;
  margin: 0 0;
  place-items: center;
  height: 100px;
}
</style>
