# front-interview
프론트개발자 면접준비


# 🍖개발 기본1

## Java와 Javascript의 차이점

-   Java: 객체지향 프로그래밍 언어 - 컴파일러 언어(C)
-   JS : 객체지향 스크립트 언어 - 인터프리터 언어(python)

## 컴파일 언어와 인터프리터 언어

-   컴파일 언어 : 한 번에 코드를 모두 읽고 실행하지만 메모리 차지가 많고 오래걸린다
-   인터프리터 언어 : 한줄 단위로 코드를 변환해서 실행한다. 처음에는 빠르지만 과정이 반복될 경우 변환과정을 계속 걸쳐야한다.

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
