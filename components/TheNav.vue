<template>
  <div class="nav">
    <NuxtLink to="/" class="nav-item" active-class="active">Index Page</NuxtLink>

    <ClientOnly>
      <NuxtLink to="/1" class="nav-item" active-class="active">Page #1</NuxtLink>
    </ClientOnly>
  </div>
</template>

<style scoped>
.nav {
  display: flex;
  justify-content: center;
  gap: 1rem;
  margin-bottom: 1rem;
  font-family: monospace;
}

.nav-item {
  text-decoration: none;
  color: #fff3;
}

.nav-item.active {
  color: #fff;
}
</style>