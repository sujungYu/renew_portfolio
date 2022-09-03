<template>
  <div class="introduce-container">
    <rainbow></rainbow>
    <!-- <div class="background-blur" v-show="introduce"></div> -->
    <div class="text-container">
      <h1 data-aos="fade-down" data-aos-delay="1000">
        무지개처럼
      </h1>
      <h2 data-aos="fade-down" data-aos-delay="1500">
        다양한 사람들과 어울리는 것을 좋아하는
      </h2>
      <h2 data-aos="fade-down" data-aos-delay="1500">
        <span class="name">유수정</span><span class="end">입니다.</span>
      </h2>
      <h3 data-aos="fade-down" data-aos-delay="3000">
        다양한 분야의 사람들과 어우러지는 프론트엔드 개발자가 되기 위해서
      </h3>
      <h3 data-aos="fade-down" data-aos-delay="3000">
        디자인, 백앤드 등 다른 분야에 대한 지식도 넓혀가고 있습니다.
      </h3>
    </div>
    <info-btn></info-btn>
  </div>
</template>

<script>
import InfoBtn from '../InfoBtn.vue';
import Rainbow from '../Rainbow.vue';
export default {
  components: {
    Rainbow,
    InfoBtn,
  },
  // data() {
  //   return {
  //     introduce: false,
  //   };
  // },
  // created() {
  //   setTimeout(() => (this.introduce = true), 1000);
  // },
};
</script>

<style scoped>
/* .background-blur {
  width: 100%;
  height: 100vh;
  background-color: rgba(253, 250, 261, 0.2);
  position: absolute;
  animation: introduce ease-in-out 0.5s normal both;
} */

/* @-webkit-keyframes introduce {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
} */
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
  color: #eb4747;
}
.text-container h3 {
  margin: 1vh auto;
  text-align: center;
  font-size: 2rem;
  color: black;
}
.end {
  color: black;
}
.name {
  /* color: #eb4747; */
  color: black;
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
  background-color: #eb4747;
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
</style>
