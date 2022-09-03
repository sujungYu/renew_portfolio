<template>
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
      <slot name="update"></slot>
    </div>
    <div class="icon-container">
      <i class="fa-brands fa-github"></i>
      <i class="fa-solid fa-globe"></i>
      <i class="fa-solid fa-camera"></i>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.projectform-container {
  position: relative;
  padding: 3vh 3vw;
  border: 3px solid black;
  border-radius: 15px;
}
.title-container {
  position: absolute;
  top: -3vh;
  left: -2vw;
  display: inline-block;
  border: 3px solid black;
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
  background-color: rgb(255, 115, 150);
  border-radius: 15px;
  color: white;
  font-size: 2rem;
  padding: 0 1vw;
  height: 4vh;
  line-height: 3.5vh;
}
.icon-container {
}
</style>
