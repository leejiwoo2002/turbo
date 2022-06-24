## 예제 포인트
1. 빌드 캐싱 + (원격 캐싱)
2. pipeline : 빌드 하기 전에 lint, test를 먼저 돈다던가, dependency 패키지의 lint,build를 먼저 돌린다던가 등의 설정
3. eslint, tsconfig의 패키지화 및 불러오기

## 예제 실행 방법

1. yarn 의존성 설치 `yarn install`
2. `yarn build`

## 원격 캐싱을 활성화 하고 싶으시다면

1. vercel 계정을 만들어주세요
2. `npx turbo login`
3. `npx turbo link`
