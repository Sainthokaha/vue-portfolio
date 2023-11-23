<template>
  <div class="main-container">
    <div class="projects-card" v-for="(items, index) in projectData.ProjectsArray" v-bind:key="items">
      <h2>{{ projectData.ProjectsArray[index].Title }}</h2>
      <img :src="projectData.ProjectsArray[index].Image" alt="">
      <p>{{ projectData.ProjectsArray[index].About }}</p>
      <div class="links">
        <a href="https://google.com/" target="_blank"><img src="../assets/github (1).svg" alt=""></a>
        <a href="" target="_blank"><img src="../assets/link.svg" alt=""></a>
      </div>
    </div>
  </div>
</template>

<script>
  import jsonData from "/projects.json"

  export default {
    data() {
      return  {
        projectData: jsonData
      }
    }
  }
</script>

<style scoped>
  .main-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
  }

  .projects-card {
    margin: 10px;
    padding: 10px;
    flex-wrap: 0 0 40%;
    background-color: #fff;
    border-radius: 25px;
    box-shadow:rgba(0, 0, 0, 0.24) 0px 3px 8px;
  }

  .projects-card img{
    height: 10rem;
  }

  .links {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
  }

  .links img {
    height: 2rem;
    margin: 5px;
  }
</style>