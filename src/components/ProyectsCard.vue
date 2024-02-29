<template>
  <div class="mainContainer">
    <div
      class="projectContainer"
      v-for="(project, index) in projectData.projectsArray"
      :key="index"
      :class="{ expanded: isExpanded(index) }"
    >
      <h2>{{ project.title }}</h2>
      <img :src="project.image" alt="" />
      <button @click="toggleExpansion(index)">
        {{ isExpanded(index) ? "Read less" : "Read more" }}
      </button>
      <p>
        {{ isExpanded(index) ? project.About : truncatedText(project.About) }}
      </p>
    </div>
  </div>
</template>

<script>
import jsonData from "../../projects.json";

export default {
  data() {
    return {
      projectData: jsonData,
      expandedIndices: [],
    };
  },
  methods: {
    truncatedText(text) {
      return text.length > 100 ? text.slice(0, 100) + "..." : text;
    },
    toggleExpansion(index) {
      if (this.isExpanded(index)) {
        this.expandedIndices = this.expandedIndices.filter((i) => i !== index);
      } else {
        this.expandedIndices.push(index);
      }
    },
    isExpanded(index) {
      return this.expandedIndices.includes(index);
    },
  },
};
</script>

<style scoped>
.mainContainer {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  /* color: aliceblue; */
  /* border: solid black 1px; */
}

.projectContainer {
  margin: 10px;
  border-radius: 20px;
  /* border: solid black 1px; */
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 300px;
  max-height: 250px;
  overflow: hidden;
  box-shadow: 3px 3px 5px rgba(255, 255, 255, 0.3);
  background-color: #c5ccf5;
}

.projectContainer img {
  height: auto;
  width: 15rem;
  border-radius: 10px;
}

.projectContainer.expanded {
  max-height: none; 
  /* max-width: none; */
  overflow: auto; 
}

.projectContainer button {
  border: none;
  border-radius: 20px;
  box-shadow: 3px 3px 5px rgba(0, 0, 0, 0.3);
  margin-top: 5px;
  background-color: #E8EBF8;

}

.projectContainer p {
  margin: 5px;
}
</style>
