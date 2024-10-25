# javascript-racingcar-precourse

# 자동차 경주

## ✅ 구현할 기능 목록

### 1️⃣ 입력

사용자는 경주할 자동차 이름과 시도할 횟수를 입력한다.

-   [ ] `@woowacourse/mission-utils` 의 `Console.readLineAsync()` 을 사용해 입력받기
    ```
    경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
    pobi,woni,jun
    시도할 횟수는 몇 회인가요?
    5
    ```

#### 🚨 에러 검토

-   [ ] 자동차 이름은 쉼표(,)를 기준으로 구분하며 이름은 5자 이하만 가능하다.
-   [ ] 시도할 횟수가 입력되지 않을 경우

### 2️⃣ 자동차 경주

-   자동차 이동 규칙
    주어진 횟수 동안 각 자동차는 전진하거나 멈출 수 있다.

    -   전진 조건: 0에서 9 사이 무작위 값을 구한 후, 값이 4 이상일 경우 전진한다.
  
- [ ] 각 자동차별로 랜덤수를 받아 전진, 멈춤 여부를 자동차 이름과 함께 출력한다. 이를 시도횟수만큼 반복한다. 

    ```
    실행 결과
    pobi : -
    woni :
    jun : -

    pobi : --
    woni : -
    jun : --

    pobi : ---
    woni : --
    jun : ---

    pobi : ----
    woni : ---
    jun : ----

    pobi : -----
    woni : ----
    jun : -----
    ```

### 3️⃣ 최종 결과 출력

-   [ ] `@woowacourse/mission-utils` 의 `Console.print()` 을 사용해 우승자 출력
-   단독 우승자 안내 문구
    ```
    최종 우승자 : pobi
    ```
-   공동 우승자 안내 문구
    ```
    최종 우승자 : pobi, jun
    ```
