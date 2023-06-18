<template>
  <div class="page">
    <h1 class="title">{{ title }}</h1>

    Some page data:
    <pre class="body"><slot /></pre>
  </div>
</template>

<script setup>
defineProps(['title'])
</script>

<style scoped>
.page {
  background: #fff1;
  color: #fffa;
  padding: 2rem;
  border-radius: 2rem;
  font-family: monospace;
}

.title {
  text-align: center;
  font-size: 36px;
  font-weight: bold;
  font-family: sans-serif;
}

.body {
  background: #000;
  border-radius: 1rem;
  padding: 2rem;
  overflow: auto;
}
</style>