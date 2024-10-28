# javascript-racingcar-precourse

## 기능 요구 사항

- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 각 자동차에 이름을 부여할 수 있다. 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
- 사용자는 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한 명 이상일 수 있다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 사용자가 잘못된 값을 입력할 경우 "[ERROR]"로 시작하는 메시지와 함께 Error를 발생시킨 후 애플리케이션은 종료되어야 한다.

## 기능 목록 단위

- [x] 1. 자동차 이름 입력받기

  - [x] 자동차 이름을 쉼표로 구분하기
  - [x] 5자 초과 또는 잘못된 입력 시 오류 발생

- [x] 2. 시도할 횟수 입력받기

  - [x] 숫자로 입력받고, 잘못된 입력 시 오류 발생

- [x] 3. 자동차 경주 현황 출력하기

  - [x] 0과 9 사이의 난수가 4 이상인 경우 한 칸 진행
  - [x] 회차마다 각 자동차의 진행 상황을 한 줄씩 출력

- [x] 4. 최종 우승자 출력하기

  - [x] 여러 우승자의 경우 쉼표로 구분하여 출력

- [x] 5. 테스트 코드 작성

  - [x] Jest 를 이용하여, 위 1, 2, 3, 4 가 제대로 기능하는지, 출력값은 정확한지를 테스트한다.
