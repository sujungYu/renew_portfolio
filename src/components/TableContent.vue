<template>
  <div>
    <nav>
      <div class="class">
        <span>Skills</span>
        <ul>
          <li><i class="fa-solid fa-circle"></i> design</li>
          <li><i class="fa-solid fa-circle"></i> frontend</li>
          <li><i class="fa-solid fa-circle"></i> backend</li>
        </ul>
      </div>
      <div class="class">
        <span>Projects</span>
        <ul>
          <li><i class="fa-solid fa-circle"></i> 코로나19 웹사이트</li>
          <li><i class="fa-solid fa-circle"></i> offco 애플리케이션</li>
          <li><i class="fa-solid fa-circle"></i> 3355 애플리케이션</li>
          <li><i class="fa-solid fa-circle"></i> 포트폴리오 웹사이트</li>
          <li><i class="fa-solid fa-circle"></i> news 웹사이트</li>
          <li><i class="fa-solid fa-circle"></i> 학습 노트 애플리케이션</li>
        </ul>
      </div>
      <div class="class">
        <span>Education</span>
        <ul>
          <li><i class="fa-solid fa-circle"></i> 상명대학교</li>
        </ul>
      </div>
      <div class="class">
        <span>Information</span>
        <ul>
          <li><i class="fa-solid fa-circle"></i> Phone</li>
          <li><i class="fa-solid fa-circle"></i> E-mail</li>
          <li><i class="fa-solid fa-circle"></i> Github</li>
          <li><i class="fa-solid fa-circle"></i> Resume</li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Jua&family=Noto+Sans+KR:wght@900&family=Rubik:wght@500&display=swap');
ul {
  list-style: none;
  padding-left: 5px;
}
li {
  font-size: 1.4rem;
  margin-bottom: 0.5vh;
  font-family: 'Noto Sans KR', sans-serif;
  /* font-weight: normal; */
}
.class {
  margin-bottom: 3vh;
}
span {
  position: relative;
  font-family: 'Kanit', sans-serif;
  /* display: inline-block; */
  font-size: 2.5rem;
  /* width: 100%; */
  color: rgb(54, 79, 107);
}
.class span::after {
  content: '';
  /* display: inline-block; */
  position: absolute;
  z-index: -1;
  left: 0;
  /* bottom: 21px; */
  top: 23px;
  width: 100%;
  height: 4px;
  /* opacity: 1; */
  background-color: rgb(252, 81, 133);
}
.fa-circle {
  font-size: 1rem;
  color: rgb(54, 79, 107);
}
li {
  display: flex;
}
li i {
  margin-right: 3px;
  margin-top: 7px;
}
</style>
