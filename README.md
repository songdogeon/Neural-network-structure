# Neural-network-structure
신경망 구조 학습및 구현

### 신경망 구조

##### 퍼셉트론
- 인공신경망의 한 종류로, 다수의 입력과 다수의 가중치를 곱하여 그값에 편향을 더한 값이 어느 임꼐치 값을 초과하면 활성화 함수를 통과한 출력값을 내보냄
- 뉴런의 수학적 표현 y=f(∑iwixi+b)
- AND 게이트 구현
- OR 게이트 구현
- NAND 게이트 구현
- XOR 게이트 해결 불가능 -> 다층퍼셉트론

##### 다층 퍼셉트론
- XOR 게이트 구현
 - AND, NAND, OR 게이트를 조합하여 해결
- 활성화 함수
 - sigmoid
 - ReLU
 - tanh
 - iodentify Function
 - Softmax
 
##### 3층 신경망 구현
- 2클래스 분류
- 입력층
 - 뉴런수 = 3
- 은닉층
 - 첫번째 은닉층
  - 뉴런수 = 3
 - 두번째 은닉층
  - 뉴런수 = 2
- 출력층
 - 뉴런수 = 2
- 신경망 추론
