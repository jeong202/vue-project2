# vue를 이용한 포트폴리오 사이트 만들기
뷰(Vue.js)는 현대적인 웹 애플리케이션 개발을 위한 프로그레시브 프레임워크입니다. 다음은 뷰의 주요 특장점들입니다:   

가볍고 빠른 속도: 뷰는 가볍고 성능이 우수하여 웹 애플리케이션의 로딩 속도를 향상시킬 수 있습니다. 가볍기 때문에 초기 다운로드 크기가 작고, 가상 DOM(Virtual DOM)을 사용하여 최소한의 업데이트만 수행하여 효율적인 렌더링을 제공합니다.   
직관적인 문법: 뷰는 간결하고 직관적인 문법을 제공하여 개발자가 쉽게 코드를 작성할 수 있습니다. HTML, CSS, JavaScript를 사용하는 개발자들에게 친숙한 문법을 사용하기 때문에 학습 곡선이 낮고 생산성이 높습니다.   
컴포넌트 기반 아키텍처: 뷰는 컴포넌트 기반 아키텍처를 채택하여 애플리케이션을 작은 단위로 나누고 재사용할 수 있게 합니다. 이를 통해 코드의 가독성과 유지보수성이 향상되며, 개발자들은 컴포넌트를 조합하여 복잡한 애플리케이션을 구축할 수 있습니다.   
양방향 데이터 바인딩: 뷰는 양방향 데이터 바인딩을 지원하여 데이터의 변경을 자동으로 반영할 수 있습니다. 이를 통해 개발자는 데이터와 UI를 동기화할 필요 없이 간단하게 상태 관리를 할 수 있습니다.   
확장성과 생태계: 뷰는 다양한 확장성과 풍부한 생태계를 가지고 있습니다. 공식 및 커뮤니티에서 제공하는 다양한 플러그인, 라이브러리, 도구 등을 활용하여 개발자들은 더욱 효율적으로 애플리케이션을 개발할 수 있습니다.
이러한 특장점들로 인해 뷰는 많은 개발자들에게 선택되고 있으며, 현대적이고 반응형인 웹 애플리케이션을 개발하는 데에 적합한 프레임워크입니다.   

## 셋팅
`npm init vue@latest`   
√ Project name: ... vue-project   
√ Add TypeScript? ... <span style="color: blue">No</span> / Yes   
√ Add JSX Support? ... No / <span style="color: blue">Yes</span>    
√ Add Vue Router for Single Page Application development? ... No / <span style="color: blue">Yes</span>   
√ Add Pinia for state management? ... <span style="color: blue">No</span> / Yes   
√ Add Vitest for Unit Testing? ... <span style="color: blue">No</span> / Yes   
√ Add an End-to-End Testing Solution? » <span style="color: blue">No</span>   
√ Add ESLint for code quality? ... No / <span style="color: blue">Yes</span>   
√ Add Prettier for code formatting? ... No / <span style="color: blue">Yes</span>   
gsap 설치 : `npm install gsap`   
sass 설치 : `npm install sass`   
lenis 설치 : `npm i @studio-freight/lenis`   



