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
          <li><i class="fa-solid fa-circle"></i> offco 웹앱</li>
          <li><i class="fa-solid fa-circle"></i> 3355 웹앱</li>
          <li><i class="fa-solid fa-circle"></i> news 웹</li>
          <li>
            <i class="fa-solid fa-circle"></i> 학습 노트 CRUD 애플리케이션
          </li>
          <li><i class="fa-solid fa-circle"></i> 포트폴리오</li>
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
  font-size: 1.3rem;
  font-family: 'Noto Sans KR', sans-serif;
  /* font-weight: normal; */
}
span {
  font-family: 'Rubik', sans-serif;
  font-size: 2rem;
}
.fa-circle {
  font-size: 1rem;
  color: rgb(79, 152, 202);
}
</style>
