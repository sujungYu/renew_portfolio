<template>
  <div>
    <project-form>
      <h2 slot="title">코로나19 웹사이트</h2>
      <span slot="tech">moment.js</span>
      <h3 slot="num">개인프로젝트</h3>
      <h4 slot="explain">
        <ul>
          <li>
            <i class="fa-solid fa-check"></i> 코로나19 관련 정보를 제공하기 위해
            개발
          </li>
          <li>
            <i class="fa-solid fa-check"></i>공공 데이터에서 제공하는 open api를
            활용
          </li>
          <li>
            <i class="fa-solid fa-check"></i>
            moment를 이용해 날짜 변동에 따른 데이터 자동 업로드가 가능하도록
            구현
          </li>
          <li>
            <i class="fa-solid fa-check"></i>우리나라 topojoson 데이터를 활용
          </li>
          <li><i class="fa-solid fa-check"></i> d3를 활용해 데이터 시각화</li>
          <li>
            <i class="fa-solid fa-check"></i> vue-router을 이용해 시, 도별
            코로나 확진자 및 백신 접종자 확인 가능
          </li>
          <li>
            <i class="fa-solid fa-check"></i> vue-chartjs을 이용해 최근 7일내
            확진자를 한 눈에 볼 수 있도록 구현
          </li>
          <li>
            <i class="fa-solid fa-check"></i>xml-js를 이용해 xml 데이터를
            json으로 파싱
          </li>
        </ul>
      </h4>
      <h5 slot="update">2021.1.1</h5>
    </project-form>
  </div>
</template>

<script>
import ProjectForm from '../common/ProjectForm.vue';
export default {
  components: {
    ProjectForm,
  },
};
</script>

<style scoped></style>
