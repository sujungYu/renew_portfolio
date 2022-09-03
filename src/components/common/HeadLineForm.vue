<template>
  <div class="text">
    <h1>
      <slot></slot>
    </h1>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.text {
  position: relative;
  top: 10vh;
  text-align: center;
  width: 50vw;
  margin: 0 auto;
  font-size: 2rem;
  font-family: 'Signika Negative', sans-serif;
  z-index: 2;
}
h1 {
  width: 100%;
  margin: 0 auto;
  background-color: white;
  border: 3px solid black;
  border-radius: 15px;
}
</style>
