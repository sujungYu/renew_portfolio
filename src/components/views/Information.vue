<template>
  <div class="information-container">
    <!-- <h1>Information</h1> -->
    <info-btn></info-btn>
    <h1>Copyright 2022. Yu Su Jung. All rights reserved.</h1>
  </div>
</template>

<script>
import InfoBtn from '../InfoBtn.vue';
export default {
  components: { InfoBtn },
};
</script>

<style scoped>
.information-container {
  background-color: rgb(54, 79, 107);
  width: 100%;
  padding: 20px 0;
}
.information-container h1 {
  margin-top: 14px;
  color: white;
  font-family: 'Noto Sans KR', sans-serif;
  font-weight: 400;
  text-align: center;
  font-size: 1.3rem;
}
</style>
