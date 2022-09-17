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

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Kanit&family=Noto+Sans+KR:wght@400;900&family=Rubik:wght@500&display=swap');
.headline-container h1 {
  position: relative;
  font-size: 7rem;
  font-family: 'Kanit', sans-serif;
  font-weight: bold;
  color: rgb(54, 79, 107);
  @include mobile {
    font-size: 5rem;
    margin-left: 5%;
  }
}
.headline-container h1::after {
  content: '';
  position: absolute;
  z-index: -1;
  left: 0;
  bottom: 17px;
  width: 90%;
  height: 10px;
  background-color: rgb(252, 81, 133);
  @include mobile {
    width: 95%;
    // margin-left: 10%;
  }
}
</style>
