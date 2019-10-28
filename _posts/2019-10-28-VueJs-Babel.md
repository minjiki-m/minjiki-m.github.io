---
layout: post
title:  "Vue.js 그리고 Babel"
date:   2019-10-28 18:15:15 +0900
categories: dev update
---


#### Vue.js
[vue doc][move-vue]에서 가져옴

사용자 인터페이스를 만들기 위한 진보적인 프레임워크.
다른 단일형 프레임워크와 달리 Vue는 점진적으로 채택할 수 있도록 설계 되었다.
핵심 라이브러리는 뷰 레이어만 초점을 맞추어 다른 라이브러리나 기존 프로젝트와의 통합이 매우 쉽다. 
Vue는 현대적 도구 및 지원하는 라이브러리와 함께 사용한다면 정교한 단일 페이지 응용프로그램을 완벽하게 지원할 수 있다.




#### BABEL
[babel doc][move-babel]에서 가져옴
Babel은 ECMAScript 2015+ 코드를 현재 및 이전 버전의 브라우저 또는 환경에서 이전 버전과 호환되는 JavaScript 버전으로 변환하는 데 주로 사용되는 툴체인입니다. 

Transform syntax
Polyfill features that are missing in your target environment (through @babel/polyfill)
Source code transformations (codemods)
And more! (check out these videos for inspiration)// Babel Input: ES2015 arrow function

- ES2015 이상
Babel은 구문 변환기를 통해 최신 버전의 JavaScript를 지원합니다.
- JSX와 반응
바벨은 JSX 구문을 변환 할 수 있습니다! 시작하려면 React 사전 설정 을 확인하십시오 . babel-sublime 패키지 와 함께 사용하여 구문 강조를 완전히 새로운 수준으로 끌어 올립니다.

[move-vue]:[https://kr.vuejs.org]
[move-bable]:[https://babeljs.io/docs/en]