<template>
  <div class="rainbow">
    <div class="arc arc-red"></div>
    <div class="arc arc-orange"></div>
    <div class="arc arc-yellow"></div>
    <div class="arc arc-green"></div>
    <div class="arc arc-blue"></div>
    <div class="arc arc-purple"></div>
    <div class="arc arc-transparent"></div>
  </div>
</template>

<script>
export default {};
</script>

<style>
@-webkit-keyframes spin {
  from {
    transform: rotateZ(-180deg);
  }
  to {
    transform: rotateZ(0deg);
  }
}
@keyframes spin {
  from {
    transform: rotateZ(-180deg);
  }
  to {
    transform: rotateZ(0deg);
  }
}

.rainbow {
  clip: rect(0 490px 245px 0);
  height: 490px;
  left: 50%;
  position: absolute;
  top: 30%;
  transform: translateX(-50%) translateY(-25%);
  width: 490px;
}

.arc {
  -webkit-animation: spin ease-in-out 0.5s normal both;
  animation: spin ease-in-out 0.5s normal both;
  border-radius: 50%;
  left: 50%;
  position: absolute;
  top: 50%;
}

.arc-red {
  background: #e31d28;
  clip: rect(0 490px 245px 0);
  height: 490px;
  margin-left: -245px;
  margin-top: -245px;
  width: 490px;
  -webkit-animation-delay: 0.6s;
  animation-delay: 0.6s;
}

.arc-orange {
  background: #ed8c3d;
  clip: rect(0 420px 210px 0);
  height: 420px;
  margin-left: -210px;
  margin-top: -210px;
  width: 420px;
  -webkit-animation-delay: 0.5s;
  animation-delay: 0.5s;
}

.arc-yellow {
  background: #fcd234;
  clip: rect(0 350px 175px 0);
  height: 350px;
  margin-left: -175px;
  margin-top: -175px;
  width: 350px;
  -webkit-animation-delay: 0.4s;
  animation-delay: 0.4s;
}

.arc-green {
  background: #3e9965;
  clip: rect(0 280px 140px 0);
  height: 280px;
  margin-left: -140px;
  margin-top: -140px;
  width: 280px;
  -webkit-animation-delay: 0.3s;
  animation-delay: 0.3s;
}

.arc-blue {
  background: #295167;
  clip: rect(0 210px 105px 0);
  height: 210px;
  margin-left: -105px;
  margin-top: -105px;
  width: 210px;
  -webkit-animation-delay: 0.2s;
  animation-delay: 0.2s;
}

.arc-purple {
  background: #492245;
  clip: rect(0 140px 70px 0);
  height: 140px;
  margin-left: -70px;
  margin-top: -70px;
  width: 140px;
  -webkit-animation-delay: 0.1s;
  animation-delay: 0.1s;
}

.arc-transparent {
  background: white;
  clip: rect(0 70px 35px 0);
  height: 70px;
  margin-left: -35px;
  margin-top: -35px;
  width: 70px;
  -webkit-animation-delay: 0s;
  animation-delay: 0s;
}
</style>
