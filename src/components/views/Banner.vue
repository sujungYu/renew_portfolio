<template>
  <div class="introduce-container">
    <rainbow></rainbow>
    <div class="text-container">
      <h1 data-aos="fade-down" data-aos-delay="1000">
        무지개처럼
      </h1>
      <h2 data-aos="fade-down" data-aos-delay="1500">
        <p>
          다양한 사람들과 어울리는 것을 좋아하는
        </p>
        <p><span class="name">유수정</span><span class="end">입니다.</span></p>
      </h2>
      <h3 data-aos="fade-down" data-aos-delay="3000">
        <p>다양한 분야의 사람들과 어우러지는 프론트엔드 개발자가 되기 위해서</p>
        <p>디자인, 백앤드 등 다른 분야에 대한 지식도 넓혀가고 있습니다.</p>
      </h3>
      <!-- <info-btn></info-btn> -->
      <i class="fa-solid fa-chevron-down"></i>
    </div>
  </div>
</template>

<script>
// import InfoBtn from '../InfoBtn.vue';
import Rainbow from '../Rainbow.vue';
export default {
  components: {
    Rainbow,
    // InfoBtn,
  },
};
</script>

<style scoped>
.introduce-container {
  width: 100%;
  height: 100vh;
  /* z-index: 1; */
  position: relative;
}
.text-container {
  font-family: 'Noto Sans KR', sans-serif;
  position: relative;
  top: 15%;
}
.text-container h1 {
  margin: 0 auto;
  font-size: 8rem;
  color: white;
  padding: 10vh 0;
  letter-spacing: 10px;
  text-align: center;
}
.text-container h2 {
  margin: 0 auto;
  /* position: relative; */
  /* top: 25%; */
  /* font-family: 'Noto Sans KR', sans-serif; */
  text-align: center;
  font-size: 3.8rem;
  color: rgb(54, 79, 107);
}
.text-container h3 {
  margin: 3vh auto;
  text-align: center;
  font-size: 2.1rem;
  color: rgb(252, 81, 133);
}
h2 p {
  margin: 1vh auto;
}
h3 p {
  margin: 2vh auto;
}
.end {
  color: rgb(54, 79, 107);
}
.name {
  /* color: #eb4747; */
  color: rgb(54, 79, 107);
  /* color: #ed8c3d; */
  /* -webkit-text-stroke: 2px black; */
  position: relative;
  z-index: 0;
  font-size: 6rem;
}
.name::after {
  content: '';
  display: inline-block;
  position: absolute;
  z-index: -1;
  left: 0;
  bottom: 10px;
  width: 100%;
  height: 10px;
  opacity: 1;
  background-color: rgb(252, 81, 133);
  animation: typing 1s 2s backwards;
}
@keyframes typing {
  from {
    width: 0%;
    z-index: -1;
  }
  to {
    width: 100%;
    z-index: -1;
  }
}
.fa-chevron-down {
  position: relative;
  top: 2vh;
  font-size: 3rem;
  color: rgb(54, 79, 107);
  display: block;
  text-align: center;
  animation: animateDown 1.5s infinite;
  /* margin-top: 10vh; */
}
@keyframes animateDown {
  0%,
  20%,
  50%,
  80%,
  100% {
    transform: translateY(0);
  }
  40% {
    transform: translateY(10px);
  }
  60% {
    transform: translateY(8px);
  }
}
</style>
