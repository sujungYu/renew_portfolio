<template>
  <div class="skills-container">
    <head-line-form>Skills</head-line-form>
    <template v-if="pc">
      <div>
        <img class="skills" src="@/assets/images/skills.png" />
      </div>
    </template>

    <template v-if="mobile">
      <div class="mobile-container">
        <img class="front" src="@/assets/images/front.png" />
        <div class="sub">
          <img class="design" src="@/assets/images/design.png" />
          <img class="back" src="@/assets/images/back.png" />
        </div>
      </div>
    </template>
  </div>
</template>

<script>
import HeadLineForm from '@/components/common/HeadLineForm.vue';
export default {
  components: {
    HeadLineForm,
  },
  data() {
    return {
      mobile: false,
      pc: false,
    };
  },
  created() {
    if (window.innerWidth < 380) {
      this.pc = false;
      this.mobile = true;
    } else {
      this.mobile = false;
      this.pc = true;
    }
  },
};
</script>

<style scoped lang="scss">
.skills {
  width: 90%;
  height: auto;
}
.design,
.back {
  // height: 10vh;
  height: 26vh;
  width: auto;
}
.front {
  width: 100%;
  margin-bottom: 10vh;
}
.mobile-container {
  display: flex;
  flex-direction: column;
}
.sub {
  display: flex;
  justify-content: space-around;
}
* {
  position: relative;
  margin: 0;
  padding: 0;
  /* margin: 0 auto;
  padding: 0 auto; */
  border: 0 none;
}
.skills-container {
  height: 100vh;
  @include mobile {
    height: initial;
  }
}
/* img {
  height: 9vh;
  width: auto;
} */
.me {
  height: 20vh;
}
h1 {
  display: inline-block;
  font-size: 2.2rem;
  margin: 1vh auto;
  font-family: 'Kanit', sans-serif;
  /* border: 3px solid rgb(79, 152, 202); */
  background-color: rgb(54, 79, 107);
  padding: 0.5vh 0.5vw;
  border-radius: 5px;
  color: white;
  letter-spacing: 2px;
}
h2 {
  font-size: 1.4rem;
  margin: 1vh auto;
  font-family: 'Kanit', sans-serif;
  background-color: rgb(54, 79, 107);
  padding: 0.5vh 0.5vw;
  border-radius: 5px;
  color: white;
  font-weight: normal;
  letter-spacing: 1px;
}
.nav {
  /* margin: 20px auto; */
  width: 100%;
  /* height: 100%; */
  /* min-height: auto; */
}

.nav ul {
  position: relative;
  padding-top: 40px;
}
.nav li {
  position: relative;
  padding: 5vh 1vw;
  float: left;

  text-align: center;
  list-style: none;
}

.nav li::before,
.nav li::after {
  content: '';
  position: absolute;
  top: 0;
  right: 50%;
  width: 50%;
  height: 30px;
  border-top: 3px solid rgb(39, 39, 39);
}

.nav li::after {
  left: 50%;
  right: auto;
  border-left: 3px solid rgb(39, 39, 39);
}

.nav li:only-child::after,
.nav li:only-child::before {
  content: '';
  display: none;
}

.nav li:only-child {
  padding-top: 0;
}
.nav li:first-child::before,
.nav li:last-child::after {
  border: 0 none;
}

.nav li:last-child::before {
  border-right: 3px solid rgb(39, 39, 39);
  border-radius: 0 5px 0 0;
}

.nav li:first-child::after {
  border-radius: 5px 0 0 0;
}
.nav ul ul::before {
  content: '';
  position: absolute;
  top: 0;
  left: 50%;
  border-left: 3px solid rgb(39, 39, 39);
  width: 0;
  height: 40px;
}
</style>
