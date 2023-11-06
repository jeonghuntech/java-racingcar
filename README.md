# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)


## step1 - 학습 테스트 실습

## step2 - 문자열 덧셈 계산기 구현

### 필요 기능
  - [x] 빈값 확인 : 빈값 0으로 처리
  - [x] 데이터 파싱 : 구분자, 숫자값 분리
  - [x] 숫자값 분리 : 구분자 기준으로 분리, custom, default
  - [x] 합계

### 개선사항
- [x] 메소드가 너무 많은 일을 하지 않도록 분리하기
- [x] 책임 찾기, REDEME.md 사용하여 필요한 기능들 나열
- [x] 하나의 커밋 보다는 여러개의 커밋으로 나누어 작업 과정 표현
- [x] 양수 VO 객체 만들기
- [x] throws Exception : 테스트 코드 작성시 필요한 곳에만 추가
- [x] 테스트 이름을 조금 더 명시적으로 작성

## step3 - 자동차 경주

### 필요 기능
- UI 로직
  - [ ] 입력 View - 자동차 대수는? 시도할 회수는?
  - [ ] 결과 View - 자동차 이동 상태
- 메인 로직
  - [x] 상태 관리 :  자동차 대수, 시도 회수
  - [x] 자동차 생성
  - [x] 자동차 이동
  - [ ] 자동차 정지
  - [ ] 자동차 이동 조건 체크 : 0 ~ 9 랜덤값, 4 이상인 경우 이동