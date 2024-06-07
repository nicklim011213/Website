<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <!---<img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />--->
	<!---Test--->
    <div class="wrapper">
      <HelloWorld msg="Resume / Projects Site" />
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  max-height: 100vh;
  place-items: center;
  margin: 0 auto;
}

.logo {
  display: block;
  margin: 0 auto;
}

main
{
  margin: auto;
  place-items: center;
}
</style>
