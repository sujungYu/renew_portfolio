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
.headline-container h1 {
  display: inline-block;
  font-size: 6rem;
  font-family: 'Rubik', sans-serif;
  font-weight: bold;
  /* border-bottom: px solid rgb(79, 152, 202); */
}
.headline-container h1::after {
  content: '';
  display: inline-block;
  position: absolute;
  z-index: -1;
  left: 0;
  top: 110px;
  width: 90%;
  height: 8px;
  /* opacity: 1; */
  background-color: rgb(79, 152, 202);
  animation: typing 1s 2s backwards;
}
</style>
