# front-interview
프론트개발자 면접준비


# 🍖개발 기본1

## Java와 Javascript의 차이점

-   Java: 객체지향 프로그래밍 언어 - 컴파일러 언어(C)
-   JS : 객체지향 스크립트 언어 - 인터프리터 언어(python)

## 컴파일 언어와 인터프리터 언어

-   컴파일 언어 : 한 번에 코드를 모두 읽고 실행하지만 메모리 차지가 많고 오래걸린다
-   인터프리터 언어 : 한줄 단위로 코드를 변환해서 실행한다. 처음에는 빠르지만 과정이 반복될 경우 변환과정을 계속 걸쳐야한다.

## 쿠키와 세션의 차이점

-   쿠키는 브라우저에 저장되고 세션은 서버에 저장된다.
-   클라이언트는 세션 ID에 대해 쿠키를 사용해서 저장하고 가지고 있는다.
-   세션도 만료시간을 정할 수 있지만 브라우저가 종료되면 만료시간에 상관없이 삭제된다.
-   세션은 서버의 자원을 사용하기때문에 무분별하게 만들다보면 서버의 메모리가 감당할 수 없어질 수가 있고 속도가 느려질 수 있다.

## jwt란?

-   토큰을 사용하면 세션을 통한 방식과 달리 서버측 부하를 낮출 수 있고 능률적인 접근 권한 관리를 할 수 있으며 분산/클라우드 기반 인프라스트럭처에 더 잘 대응할 수 있다.
-    JWT는 별도 저장소가 필요치 않아 서버자원을 절약할 수 있고 인증 과정에서 다른 곳을 거칠 필요없어 효율적이다. 인증 정보를 가진 특정 서버에만 트래픽이 몰릴 일도 없다. 서버 부하를 줄이기 좋은 방식

## 일반 함수와 화살표 함수의 차이점

-   화살표 함수의 this는 바로**상위 스코프의 this**
-   일반 함수는 this가**동적으로 바인딩**됩니다. 일반 함수의 this는내부 함수, 콜백 함수: 전역 객체,객체의 메소드,생성자 함수

## 캐싱이란?

-   실제 메모리와 cpu 사이에서 빠르게 전달을 위해서 미리 데이터들을 저장해두는 좀더 빠른 메모리

## http와 https의 차이

-   https는 http에 보안기능을 추가한 것이다. 
-   https는 SSL 인정서를 통해 데이터르 암호화하고 보안 뿐 아니라 SEO에서도 이득을 준다.

## SEO란?

-   검색엔진 최적화 (키워드 선정과 메타태그정리를 하는 것이 좋다.

## CORS란?

-   한 출처(도메인)에서 실행 중이 웹 애플리케이션이 다른 출처의 자원에 접근 할 수 있도록 권한을 부여하는 브라우저 체계
-   특정 도메인에서 다른 도메인 데이터 접근을 막는다.

## 1급 객체란?

-   변수에 할당이 가능하다.
-   다른 함수를 인자로 받을 수 있다.
-   다른 함수의 결과로서 리턴 될 수 있다.

## var,let,const의 차이점

-   var : 재선언과 재할당이 가능, 선언과 동시에 undefined가 할당된다. 실행시점에 호이스팅에 의해 변수가 상단으로 이동한다.
-   let : 재선언은 불가능 하지만 재할당이 가능하다. 스코프 안에서만 호이스팅 되고 유효하다.
-   const: 재선언과 재할당 모두 불가능, 스코프 안에서만 호이스팅 되고 유효하다.

## 호이스팅이란? 

-   함수 안에 있는 선언들을 함수 유효 범위의 최상단에 선언한다.
-   함수 실행 전에 함수 안 변수값들을 모두 모아서 유효 범위의 최상단에 선언한다.
-   let,const는 스코프 안에서 호이스팅된다.  

## 클로저란?

-   내부함수는 외부함수에 접근 할 수 있지만 외부 함수는 내부함수 접근을 할 수 없다.
-   함수가 끝난 다음에도 함수 안 변수를 사용할 수 있는 JS 성질

## 함수형 프로그래밍이란?

-   함수를 1극 객체로 규정하여 하는 개발 패턴
-   함수 내부기능은 그대로 둔 채로 사이트이펙트를 최소화 하고 여러 개의 함수를 조합해서 사용한다. 

## 웹팩이란?

-   웹팩이란 최신 프런트엔드 프레임워크에서 가장 많이 사용되는 모듈 번들러
-   웹 애플리케이션을 구성하는 자원을 각각의 모듈로 보고 이를 조합해서 병합된 하나의 결과물을 만든다.
-   이전의 웹은 페이지 마다 html을 요청해서 뿌려주는 방식 이었으나 SPA 방식은 하나의 html 페이지에 여러 JS 파일을 통합한다.
-   웹팩은 연관된 JS 파일을 하나로 묶어서 관리하고 번들링해서 성능 최적화를 해준다.

## 바벨이란?

-   ES6 버전을 ES5로 변환해서 IE11에서도 코드가 작동하도록 한다.

##  Vue.js란?

-   사용자 인터페이스를 만들기 위한 SPA 프로그레시브 프레임워크 입니다. 
-   MVVM 패턴을 가져왔다

## MVVM 패턴이란?

-   Model - View - ViewModel의 약자
-   MVC  패턴에서 Controller가 ViewModel로 바뀌었다.
-   ViewModel 은 Model과는 데이터를 주고 받고, View와는 Binding, Command로 연결된다.

## MVC 패턴이란?

- Model : 애플리케이션의 정보, 데이타
- View :  사용자 인터페이스 요소
- Controller : 사용자의 액션에 대한 "이벤트"들을 처리하는 부분

## 뷰와 리액트의 차이점

-   뷰는 프레임워크이고 리액트는 라이브러리이다.
-   프레임워크와 라이브러리의 차이점은 누가 여러가지 할 일을 자동으로 해주느냐 아니면 직접하느냐에 차이에 있다.

## html 노출 순서

1.  HTML 코드를 로딩 후 파싱해서 DOM을 생성한다
2.  DOM에 CSS를 통해 스타일 규칙을 결합해서 렌더링 트리를 생성한다.
3.  렌더링 트리를 통해 레이아웃을 잡고 최종 결과물을 그려서 사용자에게 보여준다.

## 가상돔이란?

DOM 문서를 추상화한 개념으로, 변화가 많은 View를 실제 DOM에서 직접 처리하는 방식이 아닌 Virtual Dom과 메모리에서 미리 처리하고 저장한 후 실제 DOM과 동기화 하는 프로그래밍 개념

nuxt.js란?

Nuxt.js는 Vue.js 애플리케이션 개발을 보다 강력하고 사용하기 쉽게 만들어 주는 프레임워크  
CSR을 통한 렌더링은 SEO가 어렵고 트래픽이 감소한다. 

## 뷰 인스턴스란?

-   Vue.js 화면개발의 필수 단위로 new Vue({})로 생성한다. 
-    el(인스턴스 화면의 시작점), template(화면에 표시되는 요소), data(반응형이 반영된 데이터), methods(화면과 동작을 이벤트로 제어), life cycle hook와 같은 인스턴스 옵션 속성을 포함할 수 있다.

## 뷰 라이프사이클

-   beforeCreate : 가장 먼젖 실행되는 훅으로 data와 method가 호출 전이다.
-   created : data, computed, methods, watch 등이 완료된 시점으로 data를 사용할 수 있지만 템플릿이 마운트 되기 전이기 때문에 DOM에 직접 접근을 할 수 없다.
-   beforeMount : 거의 사용되지 않습니다. data 초기 세팅에는 created를 DOM에 직접 접근은 mounted를 사용합니다.
-   mounted: 컴포넌트가 DOM에 추가 된 후 호출되어 DOM에 접근이 가능합니다. 하지만 렌더링이 모두 완료된 상태에서의 작업을 하기 위해서는 this.$nextTick(()=>{});을 사용해야합니다. 
-   beforeUpdate : 컴포넌트가 재랜더링 될 때 호출 됩니다. 이미 업데이트 된 값을 가지고 있지만 이 훅 안에서 값이 변경된다고 해서 훅이 재호출 되지 않습니다.
-   updated : DOM 재랜더링 후 호출되고 재랜더링이 끝난 확신 후 작업을 위해서는 this.$nextTick(()=>{}); 을 사용해야한다. updated 훅에서 data를 수정하면 무한루프에 빠진다.
-   beforeDestroy : 컴포넌트 제거 직전에 사용된다. 
-   destroyed : 컴포넌트가 제거 된 후 호출된다. 

# 뷰 컴포넌트

뷰의 화면을 분할하여 개발할 수 있는 뷰의 기능 

## **참고링크**

[https://kr.vuejs.org/v2/guide/index.html](https://kr.vuejs.org/v2/guide/index.html)

[

시작하기 — Vue.js

Vue.js - 프로그레시브 자바스크립트 프레임워크

kr.vuejs.org



](https://kr.vuejs.org/v2/guide/index.html)

[https://medium.com/witinweb/vue-js-%EB%9D%BC%EC%9D%B4%ED%94%84%EC%82%AC%EC%9D%B4%ED%81%B4-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-7780cdd97dd4](https://medium.com/witinweb/vue-js-%EB%9D%BC%EC%9D%B4%ED%94%84%EC%82%AC%EC%9D%B4%ED%81%B4-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-7780cdd97dd4)

[

Vue.js 2.0 라이프사이클 이해하기

최근 사내에서 Vue.js로 프로젝트를 진행하고 있다. 차근차근 꼼꼼히 프레임웤을 이해하며 시작하지 않으니 여러 우여곡절이 많았다. 정리 차원에서 하나씩 포스팅하면 좋을것 같다는 생각을 했

medium.com



](https://medium.com/witinweb/vue-js-%EB%9D%BC%EC%9D%B4%ED%94%84%EC%82%AC%EC%9D%B4%ED%81%B4-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0-7780cdd97dd4)

