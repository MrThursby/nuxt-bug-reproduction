<template>
  <div class="welcome">
    <TheNav />
    <slot />
    <AppFooter>Welcome layout</AppFooter>
  </div>
</template>

<style scoped>
.welcome {
  background: #351621;
}
</style>