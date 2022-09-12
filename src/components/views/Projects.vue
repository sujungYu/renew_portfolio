<template>
  <div>
    <head-line-form>Projects</head-line-form>
    <div class="project-container">
      <project-form data-aos="fade-right">
        <h2 slot="title">코로나19 웹사이트</h2>
        <span slot="tech">
          <ul class="tech">
            <li>vue</li>
            <li>vue-router</li>
            <li>d3.js</li>
            <li>moment.js</li>
            <li>vue-chartjs</li>
          </ul>
        </span>
        <h3 slot="num">개인프로젝트</h3>
        <h4 slot="explain">
          <ul>
            <li>
              <i class="fa-solid fa-check"></i> 코로나19 관련 정보를 제공하기
              위해 개발
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 공공 데이터에서 제공하는 open
              api를 활용하여 시, 도별 코로나/백신 정보를 확인 가능하도록 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 최근 7일내 코로나 확진자 수를 한
              눈에 볼 수 있도록 그래프로 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i>
              moment 라이브러리를 활용하여 날짜 변동에 따른 데이터 자동 업로드가
              가능하도록 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i> d3 라이브러리를 활용하여
              우리나라 지도 topojoson 데이터를 시각화하여 구현
            </li>
          </ul>
        </h4>
        <a slot="git" href="https://github.com/sujungYu/covid19_web"
          ><i class="fa-brands fa-github"></i
        ></a>
      </project-form>

      <project-form data-aos="fade-left">
        <h2 slot="title">offco 애플리케이션</h2>
        <span slot="tech">
          <ul class="tech">
            <li>
              vue
            </li>
            <li>
              vuex
            </li>
            <li>
              vue-router
            </li>
            <li>
              moment.js
            </li>
            <li>
              vue-chartjs
            </li>
          </ul>
        </span>
        <h3 slot="num">팀 프로젝트</h3>
        <h4 slot="explain">
          <ul>
            <li>
              <i class="fa-solid fa-check"></i> 기존 sns의 단점을 보완한
              단체모임 sns을 제공하기 위해 개발
            </li>
            <li>
              <i class="fa-solid fa-check"></i>백엔드 1명, 프론트엔드 1명이서
              진행한 프로젝트로 디자인과 프론드엔드를 담당
            </li>
            <li>
              <i class="fa-solid fa-check"></i>figma로 스토리보드 작성 후 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i>컴포넌트 간에 통신이나 데이터를
              효율적으로 전달하도록 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 초대링크로 단체 모임 sns에
              참여할 수 있도록 구현
            </li>
            <li><i class="fa-solid fa-check"></i>자바스크립트로 캘린더 구현</li>
            <!-- <li>
              <i class="fa-solid fa-check"></i> localStorage를 이용해 로그인
              유지 기능 구현
            </li> -->
            <!-- <li>
              <i class="fa-solid fa-check"></i> Math.random()함수로 난수를
              생성하여 초대 링크 구현
            </li> -->
            <li>
              <i class="fa-solid fa-check"></i> 기능 별로 store을 모듈화하여
              분리해서 관리
            </li>
            <!-- <li>
              <i class="fa-solid fa-check"></i>vue-router을 활용하여 SPA 구현
            </li> -->
            <!-- <li><i class="fa-solid fa-check"></i>open api, momnet 사용</li> -->
          </ul>
        </h4>
        <h5 slot="update">최종 업데이트 - 2021.1.1</h5>
      </project-form>
      <project-form data-aos="fade-right">
        <h2 slot="title">3355 애플리케이션</h2>
        <span slot="tech">
          <ul class="tech">
            <li>vue</li>
            <li>vuex</li>
            <li>vue-router</li>
            <li>eslint</li>
            <li>prettier</li>
            <li>sockjs.client</li>
            <li>webstomp-client</li>
            <li>vue2-datepicker</li>
          </ul>
        </span>
        <h3 slot="num">팀 프로젝트</h3>
        <h4 slot="explain">
          <ul>
            <li>
              <i class="fa-solid fa-check"></i> 지역별로 스터디를 관리하고
              제공하기 위해 개발
            </li>
            <li>
              <i class="fa-solid fa-check"></i>백엔드 1명, 프론트엔드 1명이서
              진행한 프로젝트로 디자인과 프론드엔드를 담당
            </li>
            <li>
              <i class="fa-solid fa-check"></i>figma로 스토리보드 작성후 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i>컴포넌트 간에 통신이나 데이터를
              효율적으로 전달하도록 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i>컴포넌트를 구조화 하여 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i> sockjs-client와
              webstomp-client를 활용해 채팅 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i>ESLint를 활용해 코드를 일관성
              있게 작성
            </li>
            <li>
              <i class="fa-solid fa-check"></i> Prettier을 활용해 코드스타일을
              일관되게 유지
            </li>
            <!-- <li>
              <i class="fa-solid fa-check"></i>vue-router을 활용하여 SPA 구현
            </li> -->
            <!-- <li>
              <i class="fa-solid fa-check"></i>vue2-datepicker를 활용해 스터디
              기간 구현
            </li> -->
            <!-- <li>
              <i class="fa-solid fa-check"></i> 요청, 응답만 받는 api를 분리하여
              작성
            </li> -->
            <li>
              <i class="fa-solid fa-check"></i> 코드 스플리팅을 활용해 페이지
              로딩 속도를 개선
            </li>
            <!-- <li><i class="fa-solid fa-check"></i>views___</li> -->
          </ul>
        </h4>
        <h5 slot="update">최종 업데이트 - 2021.1.1</h5>
      </project-form>
      <project-form data-aos="fade-left">
        <h2 slot="title">포트폴리오 웹사이트</h2>
        <span slot="tech">moment.js</span>
        <h3 slot="num">개인 프로젝트</h3>
        <h4 slot="explain">
          <ul class="tech">
            <li><i class="fa-solid fa-check"></i> NVN으로 Node.js 버전 관리</li>
            <li><i class="fa-solid fa-check"></i> MongoDB</li>
            <li><i class="fa-solid fa-check"></i>ESLint</li>
            <li><i class="fa-solid fa-check"></i> Prettier</li>
            <li><i class="fa-solid fa-check"></i> 코드 스플리팅</li>
            <li><i class="fa-solid fa-check"></i> API 설정 공통화</li>
            <li><i class="fa-solid fa-check"></i> env</li>
            <li><i class="fa-solid fa-check"></i> 코드 스플리팅</li>
            <li><i class="fa-solid fa-check"></i> HTTP 헤더에 토큰 값</li>
            <li><i class="fa-solid fa-check"></i> 코드 스플리팅</li>
            <li><i class="fa-solid fa-check"></i> 액시오스 인터셉터</li>
            <li><i class="fa-solid fa-check"></i> cookie</li>
            <li><i class="fa-solid fa-check"></i> 페이지별 인증 권한 설정</li>
            <li><i class="fa-solid fa-check"></i> 테스트 코드</li>
            <li><i class="fa-solid fa-check"></i> 액시오스 인터셉터</li>

            <li>
              <i class="fa-solid fa-check"></i>vue-router을 활용하여 SPA 구현
            </li>
          </ul>
        </h4>
        <h5 slot="update">최종 업데이트 - 2021.1.1</h5>
      </project-form>
      <project-form data-aos="fade-right">
        <h2 slot="title">news 웹사이트</h2>
        <span slot="tech">moment.js</span>
        <h3 slot="num">개인 프로젝트</h3>
        <h4 slot="explain">
          <ul>
            <li>
              <i class="fa-solid fa-check"></i> 요청, 응답만 받는 api를 분리하여
              작성
            </li>
            <li>
              <i class="fa-solid fa-check"></i> Async&Await를 활용해 비동기 처리
              문제 해결
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 이벤드 버스를 활용해 스피너 구현
            </li>
            <li>
              <i class="fa-solid fa-check"></i> Mixin을 활용해 컴포넌트 간에
              공통으로 사용하고 있는 로직을 재사용
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 네비게이션 가드를 활용해 특정
              페이지에 접근 제한
            </li>
            <li><i class="fa-solid fa-check"></i> vuex 모듈화</li>
            <li>
              <i class="fa-solid fa-check"></i> 라우터 트랜지션을 활용해
              템플릿에 효과 부여
            </li>
            <li>
              <i class="fa-solid fa-check"></i> vuex 헬퍼 함수를 활용해 코드
              간단화
            </li>
          </ul>
        </h4>
        <h5 slot="update">최종 업데이트 - 2021.1.1</h5>
      </project-form>
      <project-form data-aos="fade-left">
        <h2 slot="title">학습 노트 애플리케이션</h2>
        <span slot="tech">moment.js</span>
        <h3 slot="num">개인 프로젝트</h3>
        <h4 slot="explain">
          <ul>
            <li><i class="fa-solid fa-check"></i> NVN으로 Node.js 버전 관리</li>
            <li><i class="fa-solid fa-check"></i> MongoDB로 데이터 관리</li>
            <li>
              <i class="fa-solid fa-check"></i>ESLint를 활용해 코드를 일관성
              있게 작성
            </li>
            <li>
              <i class="fa-solid fa-check"></i> Prettier를 활용해 코드스타일을
              일관되게 유지
            </li>
            <li>
              <i class="fa-solid fa-check"></i> 코드 스플리팅을 활용해 페이지
              로딩 속도 개선
            </li>
            <li><i class="fa-solid fa-check"></i> API 설정 공통화</li>
            <li><i class="fa-solid fa-check"></i> env</li>
            <li><i class="fa-solid fa-check"></i> HTTP 헤더에 토큰 값</li>
            <li><i class="fa-solid fa-check"></i> 액시오스 인터셉터</li>
            <li><i class="fa-solid fa-check"></i> cookie</li>
            <li><i class="fa-solid fa-check"></i> 페이지별 인증 권한 설정</li>
            <li><i class="fa-solid fa-check"></i> JEST로 테스트 코드 작성</li>
            <li><i class="fa-solid fa-check"></i> 액시오스 인터셉터</li>

            <!-- <li>
              <i class="fa-solid fa-check"></i>vue-router을 활용하여 SPA 구현
            </li> -->
          </ul>
        </h4>
        <h5 slot="update">최종 업데이트 - 2021.1.1</h5>
      </project-form>
    </div>
  </div>
</template>

<script>
import HeadLineForm from '../common/HeadLineForm.vue';
import ProjectForm from '../common/ProjectForm.vue';
export default {
  components: {
    ProjectForm,
    HeadLineForm,
  },
};
</script>

<style scoped>
.project-container {
  /* display: flex; */
  /* flex-direction: column; */
  width: 90%;
}
.project-container div:nth-child(even) {
  display: flex;
  justify-content: flex-end;
}
span {
  display: block;
}
.tech li {
  margin: 2px 1px;
}
li {
  display: flex;
}
li i {
  margin-right: 2px;
  margin-top: 3px;
}

/* .project-container project-form:nth-child(even) {
  background-color: red;
} */
</style>
