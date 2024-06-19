<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="white">{{ msg }}</h1>
    <h3>
      Here are some projects im working on:
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2rem;
  top: -10px;
  padding-left: 0.4vw;
}

h3 {
  padding-left: 0.5vw;
  font-size: 1.25rem;
  color: #ffffff;
}

.greetings h1,
.greetings h3 {
  text-align: left;
}
</style>
