<template>
  <div class="headline-container">
    <h1>
      <slot></slot>
    </h1>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kanit&family=Noto+Sans+KR:wght@400;900&family=Rubik:wght@500&display=swap');
.headline-container h1 {
  position: relative;
  /* display: inline-block; */
  font-size: 7rem;
  font-family: 'Kanit', sans-serif;
  font-weight: bold;
  color: rgb(54, 79, 107);
  /* border-bottom: px solid rgb(79, 152, 202); */
}
.headline-container h1::after {
  content: '';
  /* display: inline-block; */
  position: absolute;
  z-index: -1;
  left: 0;
  bottom: 20px;
  /* top: 60px; */
  width: 90%;
  height: 10px;
  /* opacity: 1; */
  background-color: rgb(252, 81, 133);
}
</style>
