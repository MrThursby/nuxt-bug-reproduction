<template>
  <div class="wrapper">
    <NuxtLayout class="layout">
      <NuxtPage/>
    </NuxtLayout>
  </div>
</template>

<style>
body {
  margin: 0;
}

.wrapper {
  height: 100vh;
  box-sizing: content-box;
  overflow: hidden;
}

.layout {
  height: 100%;
  overflow: hidden;
  padding: 14rem;
}
</style>