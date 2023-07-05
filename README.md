# wanted-pre-onboarding-challenge-fe-0
원티드 프리온보딩 프론트엔드 챌린지 7월 사전과제

#### 1. CSR(Client-side Rendering)이란 무엇이며, 그것의 장단점에 대하여 설명해주세요.
클라이언트 사이드 렌더링은 클라이언트인 브라우저가 렌더링을 처리하는 방식입니다. 즉, 서버에서 받은 데이터를 통해 클라이언트인 브라우저가 화면을 그리는 주체가 되는 것을 말합니다.  
- **장점**  
  1. 네이티브 앱과 비슷한 빠른 인터렉션을 구현할 수 있습니다.  
  2. 클라이언트 측에서 데이터를 요청하는 API는 웹 애플리케이션과 독립적으로 설계될 수 있으며, 이는 재사용 가능한 API를 구축하는데 도움이 됩니다.  

- **단점**  
  1. 첫 페이지 로딩 속도가 서버 사이드 렌더링에 비해 다소 느립니다.  
  2. 검색엔진최적화(SEO)에 대한 추가 보완 작업이 필요합니다.


    
### 2. SPA(Single Page Application)로 구성된 웹 앱에서 SSR(Server-side Rendering)이 필요한 이유에 대하여 설명해주세요.
- **SPA(Single Page Application)**  
  - 클라이언트 측에서 모든 페이지 리소스를 미리 받아오고, 필요한 데이터를 AJAX 요청을 통해 동적으로 로드하여 사용자 경험을 향상시키는 웹 애플리케이션입니다.  
  - 장점 : 빠른 페이지 전환, 부드러운 사용자 인터페이스 및 웹 애플리케이션의 반응성입니다.  

- **SSR(Server-side Rendering)**  
  - 서버에서 페이지의 초기 HTML을 렌더링하여 클라이언트에 전송하는 방식입니다.  
  - 장점 : 검색 엔진 최적화(SEO), 초기 로딩 속도 향상, 소셜 미디어 공유가 가능합니다.  


> SPA는 초기 로딩 속도에는 이점이 있지만, 애플리케이션의 첫 번째 요청에서 사용자에게 아무것도 보여주지 않기 때문에 초기 렌더링 속도가 느릴 수 있습니다.
> 따라서 SPA의 초기 로딩 속도와 검색 엔진 최적화, 소셜 미디어 공유 등에 있어서 중요한 역할을 하기 때문에 SSR이 필요합니다.  


    

### 3. Next.js 프로젝트에서 yarn start(or npm run start) 스크립트를 실행했을 때 실행되는 코드를 Next.js Github 레포지토리에서 찾은 뒤, 해당 파일에 대한 간단한 설명을 첨부해주세요.
https://nextjs.org/docs/getting-started (Next.js 세팅 가이드)
https://github.com/vercel/next.js/ (Next.js Github 레포지토리)
_document.js, _app.js, getServerSideProps 같은 요소들에 대해 설명을 요구하는 과제가 아닙니다. 오히려 Next.js 코드 베이스 내부를 살펴보라는 의미입니다.
