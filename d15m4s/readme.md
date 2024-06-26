<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=gradient&text=🎯코딩테스트%20학습%20전략🔥&fontAlign=50&fontAlignY=40&fontSize=50&desc=☁️구름톤%20유니브%20코딩테스트%20준비반🎉&descAlignY=57&textBg=false">
</div>


## 1. 코딩테스트 학습 요령

### a. 기록할 것
+ 풀이에 성공하거나 혹은 실패할 경우, 사고의 흐름을 기록하고 독하게 피드백할 것

### b. 시험 보듯이 공부할 것
+ 주어진 시간을 효율적으로 사용하여 최대의 점수를 구하는 연습을 할 것

### c. 나만의 언어로 요약할 것
+ 지금까지 학습한 로직이나 방법론에 대해 나만의 언어로 요약하고 표현할 수 있는지 확인해 볼 것
<br>

## 2. 문제풀이 분석요령

### a. 동작 단위로 쪼개어 분석
+ 분할 탐색할 것. 숲을 보는 것보다 나무를 보는 것이 머리가 덜 아프다
  
### b. 제약사항 파악하기
+ 제약사항을 빠르게 파악하고, 구현 방향성을 미리 메모해두면 좋다.
  
### c. 시간 복잡도 분석
+ 선택한 알고리즘에 대한 최악의 케이스를 분석할 것
  
### d. Edge Case 분석
+ 테스트 케이스를 추가로 구성하여 Edge Case 해결 가능성을 모색해야 한다.
  
### f. data flow 분석
+ 삽입 삭제가 빈번하게 이루어지는지, 어떠한 값이 주 대상인지 파악할 것
<br>

## 의사코드 사용요령

### a. 세부 구현 하지 말기
+ 누구나 이해할 수 있는 언어로 작성하기

### b. 해결 순서대로 작성하기
+ 실제 주석으로 쓸 수 있을 만큼 작성

### c. 테스트 많이 해보기
+ 구현 단계에서의 수정은 상당한 비용이 발생한다. Edge Case에 대한 충분한 고려가 필요하다.
<br>


## 3. 시간 복잡도 분석 요령

### 초당 연산 횟수 3,000만 정도로 고려할 것 
+ 출제자는 의도한 로직 구현 시, 대부분의 코드를 정답 처리하도록 여유 있게 설정
+ 반대로 말하자면, 초당 연산을 1억회로 잡고 계산 시, 의도와 다른 알고리즘을 선택할 가능성도 있음
### 입력값 범위 선택
1. O(N^2)   - 10개
2. O(2^N)   - 20개
3. O(N^3)   - 300개
4. O(N^2)   - 5000개
5. O(NlogN) - 1,000,000개   (100만개)
6. O(N)     - 10,000,000개  (1,000만개)
7. O(logN)  - 100,000,000개 (10억개)

+ ex) 입력값이 100만개일 경우, O(NlogN)보다 나은 알고리즘을 사용해야 한다.
