<script setup>
import MainCard from "./components/MainCard.vue";
import ProjectsCard from "./components/ProjectsCard.vue";
</script>

<template>
  <header>
    <div></div>
  </header>

  <main></main>

  <body>
    <div>
      <MainCard />
      <ProjectsCard />
    </div>
  </body>
</template>

<style scoped>
header {
  display: flex;
  background-color: #261553;
}
</style>
