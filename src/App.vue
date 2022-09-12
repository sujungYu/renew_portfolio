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
        <skills></skills>
        <projects></projects>
        <education></education>
      </div>
    </div>
    <information></information>
  </div>
</template>

<script>
import TableContent from './components/TableContent.vue';
import Banner from './components/views/Banner.vue';
import Skills from './components/views/Skills.vue';
import Projects from './components/views/Projects.vue';
import Education from './components/views/Education.vue';
import Information from './components/views/Information.vue';
export default {
  components: {
    Banner,
    TableContent,
    Skills,
    Projects,
    Education,
    Information,
  },
};
</script>

<style>
html {
  font-size: 10px;
}
body {
  margin: 0 auto;
}
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
/* a {
  text-decoration: none;
  cursor: pointer;
} */
</style>
