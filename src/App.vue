<template>
  <div>
    <div class="banner">
      <banner></banner>
    </div>
    <div class="container">
      <div class="table-container">
        <table-content></table-content>
      </div>
      <div class="views-container" id="skills">
        <!-- <introduce></introduce> -->
        <skills></skills>
        <projects></projects>
      </div>
    </div>
  </div>
</template>

<script>
import TableContent from './components/TableContent.vue';
import Banner from './components/views/Banner.vue';
// import Introduce from './components/views/Introduce.vue';
import Skills from './components/views/Skills.vue';
import Projects from './components/views/Projects.vue';
export default {
  components: { Banner, TableContent, Projects, Skills },
};
</script>

<style>
.banner {
  width: 100%;
  height: 100vh;
  background-color: white;
}
.container {
  display: flex;
  justify-content: space-between;
}
.table-container {
  position: static;
  padding: 1vh 1vw;
  /* width: 10%; */
  /* background-color: rgb(171, 201, 255); */
}
.views-container {
  width: 80%;
}
</style>
