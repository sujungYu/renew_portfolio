<template>
  <div>
    <div class="projectform-container">
      <div class="title-container">
        <slot name="title"></slot>
      </div>
      <div class="tech-container">
        <slot name="tech"> </slot>
      </div>
      <div class="content-container">
        <slot name="num"></slot>
        <slot name="explain"></slot>
        <slot name="update"> </slot>
      </div>
      <div class="icon-container">
        <i class="fa-brands fa-github"></i>
        <i class="fa-solid fa-globe"></i>
        <i class="fa-solid fa-camera"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.projectform-container {
  position: relative;
  margin-bottom: 10vh;
  padding: 5vh 3vw 0;
  border: 3px solid rgb(54, 79, 107);
  border-radius: 15px;
  width: 50%;
}
.title-container {
  position: absolute;
  top: -3vh;
  left: -2vw;
  display: inline-block;
  border: 3px solid rgb(54, 79, 107);
  border-radius: 10px;
  background-color: white;
  transform: rotate(-10deg);
  font-size: 1.5rem;
  z-index: 1;
}
.title-container h2 {
  margin: 0.5vh 0.5vw;
}
.tech-container {
  display: inline-block;
  background-color: rgb(252, 81, 133);
  border-radius: 15px;
  color: white;
  font-size: 2rem;
  padding: 0 1vw;
  height: 4vh;
  line-height: 3.5vh;
}
.content-container {
  font-family: 'Noto Sans KR', sans-serif;
  font-weight: 400;
  /* font-weight: normal; */
}
.content-container h3 {
  font-size: 2rem;
  font-weight: 400;
}
.content-container h4 {
  font-size: 1.6rem;
  font-weight: 400;
}
.content-container h5 {
  font-size: 1.4rem;
  font-weight: 400;
}
ul {
  list-style: none;
  padding-left: 10px;
}
.icon-container {
  position: absolute;
  right: 0;
  bottom: -20px;
  margin-right: 0;
  font-size: 3rem;
  background-color: white;
  /* display: flex; */
  /* width: 120px; */
  /* justify-content: flex-end; */
  /* align-items: flex-end; */
}
.icon-container i {
  margin: 0 10px;
}
</style>
