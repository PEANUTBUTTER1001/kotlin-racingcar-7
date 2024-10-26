# kotlin-racingcar-precourse

---

## 기능 목록

---

#### 1. 자동차 이름 입력

- 쉼표(,) 기준으로 이름을 구분하여 입력


#### 2. 자동차 이름 입력 오류 처리

- 오류시 `IllegalArgumentException`발생
- 오류조건
  - 미입력
  - 이름 5자 초과


#### 3. 이동 횟수 입력

   - 시도할 횟수(숫자) 입력


#### 4. 이동 횟수 입력 오류 처리

- 오류시 `IllegalArgumentException`발생
- 오류조건
  - 미입력
  - 숫자아닌 문자 입력

  
#### 5. 자동차 별 무작위 값 결과에 따른 전진

   - 각각의 자동차의 랜덤값이 4이상 나오면 전진


#### 6. 차수별 무작위 값 결과 반영 및 출력

   - 차수별로 자동차의 전진상황 출력


#### 7. 우승자 선정 계산

   - 자동차 별로 전진횟수 비교하여 최다 전진 차량을 (공동)우승자 선정


#### 8. 우승자 안내 출력

   - (공동)우승자 출력


#### 기타사항
