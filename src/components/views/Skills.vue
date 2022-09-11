<template>
  <div>
    <head-line-form>Skills</head-line-form>
    <nav class="nav">
      <ul>
        <li class="li">
          <h1>My Skills</h1>
          <!-- <img class="me" src="@/assets/images/유수정.png" /> -->
          <ul>
            <li>
              <h1>Design</h1>
              <ul>
                <li>
                  <img src="@/assets/images/photoshop.png" />
                  <h2>photoshop</h2>
                </li>
                <li>
                  <img src="@/assets/images/illustrator.png" />
                  <h2>illust</h2>
                </li>
                <li>
                  <img src="@/assets/images/figma.png" />
                  <h2>figma</h2>
                </li>
              </ul>
            </li>
            <li>
              <h1>Frontend</h1>
              <ul>
                <li>
                  <img src="@/assets/images/html.png" />
                  <h2>html</h2>
                </li>
                <li>
                  <img src="@/assets/images/css.png" />
                  <h2>css</h2>
                </li>
                <li>
                  <img src="@/assets/images/javascript.png" />
                  <h2>javascript</h2>
                </li>
                <li>
                  <img src="@/assets/images/typescript.png" />
                  <h2>typescript</h2>
                </li>
                <li>
                  <img src="@/assets/images/vue.png" />
                  <h2>vue</h2>
                </li>
                <li>
                  <img src="@/assets/images/sass.png" />
                  <h2>sass</h2>
                </li>
              </ul>
            </li>
            <li>
              <h1>Backend</h1>
              <ul>
                <li>
                  <img src="@/assets/images/node-js.png" />
                  <h2>node-js</h2>
                </li>
                <li>
                  <img src="@/assets/images/mysql.png" />
                  <h2>mysql</h2>
                </li>
              </ul>
            </li>
          </ul>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
import HeadLineForm from '@/components/common/HeadLineForm.vue';
export default {
  components: {
    HeadLineForm,
  },
};
</script>

<style scoped>
* {
  position: relative;
  margin: 0;
  padding: 0;
  /* margin: 0 auto;
  padding: 0 auto; */
  border: 0 none;
}
img {
  height: 9vh;
  width: auto;
}
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
}
.nav {
  /* margin: 20px auto; */
  width: 100%;
  /* height: 100%; */
  /* min-height: auto; */
}

.nav ul {
  position: relative;
  padding-top: 30px;
}
.nav li {
  position: relative;
  padding: 3vh 1vw;
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
  height: 20px;
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
  height: 30px;
}
</style>
