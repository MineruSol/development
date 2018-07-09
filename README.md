# 프로젝트 소개
개발의 전반적인 부분은 공부하면서 조금씩 정리 할 겸, Github를 최대한 활용을 하기 위한 프로젝트이다.

# 목차
<!-- TOC -->

- [프로젝트 소개](#%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%86%8C%EA%B0%9C)
- [목차](#%EB%AA%A9%EC%B0%A8)
- [전체 플로우](#%EC%A0%84%EC%B2%B4-%ED%94%8C%EB%A1%9C%EC%9A%B0)
    - [JavaScript](#javascript)
    - [Node.js](#node.js)
    - [TypeScript](#typescript)
    - [React](#react)
    - [Webpack](#webpack)

<!-- /TOC -->

# 전체 플로우
1. JavaScript란?
2. Node.js란?
3. TypeScript란?
4. react란?
5. Webpack이란?

## JavaScript
**JavaScript란?**

요약 : JavaScript는 웹페이지를 구성하는 언어 중 하나이며, 한 화면에서 Action을 담당한다.

웹 페이지의 내용에 대한 것은 html이, 디자인에 대한 것은 css가, 움직임은 javascript가 담당하고 있다.

## Node.js
**Node.js란?**

## TypeScript
**TypeScript란?**

## React
**React란?**

## Webpack
**Webpack이란?**

요약 : Webpack은 JavaScript의 모듈화 도구이다.

서버에서 처리하는 Logic을 JS로 구현하는 부분이 많아지면서 웹 서비스 개발에서 JS로 작성하는 코드의 양도 늘어났다.
코드의 양이 많아지면 코드의 유지&보수가 쉽도록 코드를 모듈로 나누어 관리하는 모듈 시스템이 필요해진다.
그러나 JS 자체로는 모듈 시스템이 없다. 이러한 문제를 해결하기 위한 도구가 Webpack이다.

**설치**
```
npm install webpack -g 
//작성일 기준(2018.07.09:14h) webpack 버전 : 4.15.1
```

webpack을 설치를 완료하면
```
webpack {엔트리 파일 경로} {번들 파일 경로}
ex) webpack ./entry.js bundle.js
```
형식으로 명령어를 실행해 모듈을 컴파일 한다.

엔트리 파일은 서로 의존 관계에 있는 다양한 모듈을 사용하는 시작점이 되는 파일이다. 번들 파일은 비라우저에서 실행할 수 있게 모듈을 컴파일한 파일이다.

webpack에서 컴파일은 엔트리 파일을 시작으로 의존 관계에 있는 모듈을 엮어서 하나의 번들 파일을 만드는 작업이다.

### TypeScript + React + Webpack
```
create-react-app type-react-pack --scripts-version=react-scripts-ts
npm install -D webpack webpack-cli typescript awesome-typescript-loader
```
