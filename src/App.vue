<script setup>
import MainCard from "./components/MainCard.vue";
import ProyectsCard from "./components/ProyectsCard.vue";
</script>

<template>
  <header>
    <div></div>
  </header>

  <main></main>

  <body>
    <div>
      <MainCard />
      <ProyectsCard />
    </div>
  </body>
</template>

<style scoped>
header {
  display: flex;
  background-color: #261553;
}
</style>
