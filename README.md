# kotlin-racingcar

# step2 - 사칙연산 계산기

### 기능 요구 사항
- 사용자가 입력한 문자열 값에 따라 사칙 연산을 수행할 수 있는 계산기를 구현해야 한다.
- 문자열 계산기는 사칙 연산의 계산 우선순위가 아닌 입력 값에 따라 계산 순서가 결정된다.
- 즉, 수학에서는 곱셈, 나눗셈이 덧셈, 뺄셈 보다 먼저 계산해야 하지만 이를 무시한다.
- 예를 들어 2 + 3 * 4 / 2 와 같은 문자열을 입력할 경우 2 + 3 * 4 / 2 실행 결과인 10을 출력해야 한다.



### 기능 구현 리스트
- [x] 덧셈 
- [x] 뺄셈
- [x] 곱셈
- [x] 나눗셈
- [x] 사칙연산을 모두 포함하는 연산
- [x] 입력값이 null 또는 빈 문자열일 경우 IllegalArgumentException throw
- [x] 사칙연산 기호가 아닌 경우 IllegalArgumentException throw


# step3 - 자동차 경주 게임

### 기능 요구 사항
- 초간단 자동차 경주 게임을 구현한다.
- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 무작위 값을 구한 후 무작위 값이 4 이상일 경우이다.
- 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.


### 기능 구현 리스트
- [x] n대의 자동차를 입력받을 수 있어야 한다. (양의 정수가 들어오지 않는다면 Exception 반환)
- [x] 몇번 이동을 수행할 것인지 입력할 수 있어야 한다. (양의 정수가 들어오지 않는다면 Exception 반환)
- [ ] n대의 자동차를 만들어야 한다.
- [ ] 무작위로 랜덤 전진할 수 있어야 한다.
- [ ] 경기가 종료되고 자동차의 상태를 출력할 수 있어야 한다.

