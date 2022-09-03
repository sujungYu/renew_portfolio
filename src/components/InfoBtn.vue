<template>
  <div class="button-container">
    <ul>
      <li class="li-container phone">
        <i class="fa-solid fa-phone icon"></i>
        <span class="text">010-3654-2583</span>
      </li>
      <li class="li-container mail">
        <i class="fa-solid fa-envelope icon"></i>
        <span class="text">su_moment@naver.com</span>
      </li>
      <li class="li-container github">
        <i class="fa-brands fa-github icon github"></i>
        <span class="text">Github</span>
      </li>
      <li class="li-container blog">
        <i class="fa-solid fa-b icon"></i>
        <span class="text">Blog</span>
      </li>
      <li class="li-container resume">
        <i class="fa-solid fa-file icon"></i>
        <span class="text">Resume</span>
      </li>
    </ul>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.button-container {
  position: absolute;
  bottom: 5vh;
  /* right: 1vw; */
  width: 100%;
  /* height: 100%; */
}
.button-container {
  /* position: relative;
  font-size: 1.8rem;
  width: 50px;
  height: 50px;
  border: 2px solid rgb(255, 115, 150);
  border-radius: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer; */
}
.text {
  position: absolute;
  /* font-family: 'Nanum Gothic', sans-serif; */
  top: 0;
  font-size: 1.4rem;
  /* z-index: 10; */
  z-index: -2;
  white-space: nowrap;
  /* opacity: 0;/ */
}
ul {
  width: 30%;
  padding: 0;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  /* align-items: center; */
  list-style: none;
  /* align-items: flex-end; */
}
li {
  position: relative;
  font-size: 1.8rem;
  width: 5rem;
  height: 5rem;
  border: 2px solid black;
  background-color: white;
  border-radius: 50px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}
li:hover {
  border-color: white;
}
/* .icon:hover {
  color: red;
} */
/* .icon:hover .text {
  top: -45px;
  opacity: 2;
  visibility: visible;
  pointer-events: auto;
} */
.li-container:hover .text {
  /* color: red; */
  pointer-events: none;

  top: -5vh;
  z-index: 10;
  transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
  background: #ffffff;
  color: #ffffff;
  padding: 5px 8px;
  border-radius: 5px;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.1);
  /* opacity: 1; */
  /* z-index: 2;
  opacity: 1; */
  /* visibility: visible; */
  /* pointer-events: auto; */
}
.text::before {
  position: absolute;
  content: '';
  height: 8px;
  width: 8px;
  background: #ffffff;
  bottom: -3px;
  left: 50%;
  transform: translate(-50%) rotate(45deg);
  transition: all 0.3s cubic-bezier(0.68, -0.55, 0.265, 1.55);
}
.github:hover,
.github:hover .text,
.github:hover .text::before {
  background: #333333;
  color: #ffffff;
}
.mail:hover,
.mail:hover .text,
.mail:hover .text::before {
  background: #2db400;
  color: #ffffff;
}
.phone:hover,
.phone:hover .text,
.phone:hover .text::before {
  background: black;
  color: #ffffff;
}
.resume:hover,
.resume:hover .text,
.resume:hover .text::before {
  background: #0096ff;
  color: #ffffff;
}
.blog:hover,
.blog:hover .text,
.blog:hover .text::before {
  background: rgb(123, 109, 109);
  color: #ffffff;
}
</style>
