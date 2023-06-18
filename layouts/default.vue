<template>
  <div class="default">
    <TheNav />
    <slot />
    <AppFooter>Default layout</AppFooter>
  </div>
</template>

<style scoped>
.default {
  background: #00262a;
}
</style>