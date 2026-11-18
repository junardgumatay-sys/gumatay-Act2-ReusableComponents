<template>
  <div class="layout">
    
    <AppHeader />

    <main class="container">
      <NuxtPage />
    </main>

    <AppFooter />
  </div>
</template>

<style>
body {
  margin: 0;
  font-family: time new Roman;
  background-color: #f8fafc;
  color: #0f172a;
}
.container {
  max-width: 900px;
  margin: 30px auto;
  padding: 0 20px;
  min-height: 70vh;
}
</style>