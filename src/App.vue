<template>
  <div>
    <MainCard/>
    <ProjectCard/>
  </div>
</template>

<script>
import MainCard from './components/MainCard.vue';
import ProjectCard from './components/ProjectCard.vue'
export default {
  name: 'App',
  components: {
    MainCard,
    ProjectCard
  }
}
</script>

<style>
body{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgb(218, 235, 250);
}
</style>
