## 코로나 세계 현황판 만들기

최종 프로젝트 폴더입니다

## 자바스크립트 프로젝트에 타입스크립트 적용하기
## 프로젝트 진행을 할 때의 프로세스(순서)

0. 자바스크립트 파일에 JSDoc으로 타입 시스템 입히기
1. 타입스크립트의 기본 환경 구성
    - [x] NPM 초기화
    - [x] 타입스크립트 라이브러리 설치
    - [x] 타입스크립트 설정 파일 생성 및 기본 값 추가
    - [x] 자바스크립트 파일을 타입스크립트 파일로 변환하기
    - [x] 'tsc' 명령어로 타입스크립트 변환해보기
2. 명시적인 'any' 선언하기
    - 프로젝트 테스트 코드가 통과하는 지 확인하기
    - 'tsconfig.json' 파일에 'noImplicitAny' 값을 'true'로 추가
    - 가능한 타입을 적용할 수 있는 모든 곳에 타입 적용하기
      - 만약 타입 을 정하기 어려운 곳이 있으면 명시적으로라도 any를 선언한다.
    - 테스트 코드가 통과하는 지 확인하기
3. 프로젝트 환경 구성
    - babel, eslint, prettier 등의 환경 설정
4. 외부 라이브러리 모듈화(에러나는 외부 라이브러리들(axios나 chart 같은 것들))
5. 'strict' 모드 옵션 추가 후, 타입 정의하기
6. 테스트 코드가 통과하는 지 확인하기
## 참고 자료

- [존스 홉킨스 코로나 현황](https://www.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6)
- [Postman API](https://documenter.getpostman.com/view/10808728/SzS8rjbc?version=latest#27454960-ea1c-4b91-a0b6-0468bb4e6712)
- [Type Vue without Typescript](https://blog.usejournal.com/type-vue-without-typescript-b2b49210f0b)