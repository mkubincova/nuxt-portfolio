<template>
  <div class="container">
    <Navigation />
    <main><slot /></main>
  </div>
</template>

<style>
@import url("~/assets/reset.css");

.container {
  width: 100vw;
  height: 100vh;
  overflow: hidden;
  box-sizing: border-box;
  display: grid;
  grid-template-columns: 250px 1fr;
  font-family: "Inter", sans-serif;
}

main {
  background-color: aqua;
  padding: 20px;
  max-height: 100%;
  overflow: auto;
}
</style>
