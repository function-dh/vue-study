# vue-study
20.06.08 ~ 진행중

#### 1일차 - 50p (1장, 2장, 3-1장)     
- vue 설치, 뷰 인스턴스 생성, 뷰 인스턴스 유효범위, 라이프 사이클

#### 2일차 - 75p (3-2장, 3-3장)      
- 뷰 컴포넌트(전역,로컬)내용 및 차이, 컴포넌트의 유효범위
- 상하위 컴포넌트 관계(단반향 데이터 흐름)
- props(상위에서 하위로 속성값 전달), $emit(하위에서 상위로 이벤트 발생)
- eventBus($on) / 상-하위 관계를 유지하지 않아도 데이터를 컴포넌트 -> 컴포넌트로 전달 가능 

#### 3일차 - 95p (4장)
- 뷰 라우터 기능(router-link to="url주소", router-view)
- 네스티드 라우터는 최소 2개 이상의 컴포넌트를 화면에 보여줄 수 있음(상위 -> 하위 포함, children)              
- 네임드 뷰는 특정 페이지 이동 시 같은 레벨의 여러 개의 컴포넌트를 동시에 표시할 수 있음
- http 통신 방법(브라우저 -> 요청 -> 서버 -> 응답), ajax지원 라이브러리 사용
- 뷰 리소스, 문자열 값으로 받아오기 때문에 따로 JSON.parse을 해줘야 함
- Axios액시오스 현재 많이 사용하는 HTTP 통신 라이브러리, Promise기반의 API 형식을 다양하게 제공
- Promise객체는 비동기 로직처리에 유용함(데이터 요청 후 받아 올 때까지 기다렸다가 화면에 나타낼 때 자주 사용)
- api 기본 구조 
``` javascript 
// 뷰 리소스의 경우 this.$http.get()
axios.get('')
  .then(function(data) {
  })
  // 오류 발생 시 catch구문 실행
  .catch(function(){
  });
``` 

#### 4일차 -  139p (5장, 6-1~6-3장)

#### 5일차 - 174p (6-4~6-6장)

#### 6일차 - 204p (7장)

#### 7일차 - 227p (부록)
