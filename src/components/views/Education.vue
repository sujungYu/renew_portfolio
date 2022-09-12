<template>
  <div>
    <head-line-form>Education</head-line-form>
    <h2>상명대학교</h2>
    <h3 class="edu-container">
      <ul>
        <li>
          <i class="fa-solid fa-check">
            휴먼지능로봇공학과 재학중( 2018.03 ~ )</i
          >
        </li>
        <li><i class="fa-solid fa-check"> 학점 3.8 / 4.5</i></li>
      </ul>
    </h3>
  </div>
</template>

<script>
import HeadLineForm from '../common/HeadLineForm.vue';
export default {
  components: { HeadLineForm },
};
</script>

<style scoped>
h2 {
  font-size: 3rem;
  font-family: 'Noto Sans KR', sans-serif;
  color: rgb(54, 79, 107);
}
h3 {
  font-size: 1.8rem;
  font-family: 'Noto Sans KR', sans-serif;
  color: rgb(54, 79, 107);
}
ul {
  list-style: none;
}
.edu-container {
  margin-bottom: 10vh;
}
</style>
