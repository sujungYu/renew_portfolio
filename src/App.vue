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
  components: { Banner, TableContent, Skills, Projects },
};
</script>

<style>
.banner {
  width: 100%;
  height: 100vh;
  background-color: rgb(245, 245, 245);
}
.container {
  display: flex;
  flex-flow: row nowrap;
  /* justify-content: space-between; */
  /* position: relative; */
}
.table-container {
  position: sticky;
  padding: 10vh 2vw;
  width: 10%;
  height: 100vh;
  top: 0vh;
  /* background-color: red; */
  /* background-color: rgb(171, 201, 255); */
}
.views-container {
  width: 90%;
  /* height: 200vh; */
  /* width: 80%; */
}
</style>
