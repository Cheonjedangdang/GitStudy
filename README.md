## vue 프로젝트 구성요소 정리
- [ ] pakage.json
  - 프로젝트 정보와 의존성(dependencies)을 관리하는 문서 (pom.xml 같은 거) 
- [ ] node_module
  - npm install 할 때 모듈이 설치되는 경로(m2 같은거)
- [ ] public
  - index.html: Vuejs HTML 시작페이지
- [ ] src/: 실제 대부분의 코딩이 이루어지는 디렉토리
  - assets/: 이미지 등 어플리케이션에서 사용되는 파일들이 모여 있는 디렉토리
  - components/: Vue 컴포넌트들이 모여 있는 디렉토리
  - router/: vue-router 설정을 하는 디렉토리
  - App.vue: 가장 최상위 컴포넌트
  - main.js: 가장 먼저 실행되는 javascript파일, Vue 인스턴스를 생성하는 역할
- [ ] webpack 이란
  - 현대 Javascript Application의 Static Module Bundler입니다.
  - Webpack이 실행된다면 Dependencies Graph를 통해 필요한 형태의 하나 또는 여러개의 Bundle로 생성합니다.
  - 요약 : 의존성 있는 모듈을 파일 하나 or 여러개로 묶음

