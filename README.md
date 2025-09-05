# Journey to Become an AI Developer
안녕하세요! AI 개발자를 목표로 매일 꾸준히 공부하고 기록하는 공간입니다!

---

### TIL(Today I Learned)

## 2025 - 09 - 04 (목)
- **python study** : 오늘 배운것, f 포메이션. print(f"{score_sum = }")
  - 새로 알게된 것 :
    -f 포메이션의 의미는 f"~~" 에 있는 "~" 부분에 문자열을 출력하는데 그 사이 {} 중괄호 안에 값을 미리 입력해둔 변수로 출력가능하다.
    -f 포메이션에서 print(f"{score_sum = }") 처럼 중괄호 안에 등호 = 기호를 넣을 수 있고, 이때 의미는 중괄호 안에 변수와 등호, 그리고 변수에 할당된 값을 출력하는 것이다.
    - += 이거 말고도 *= , /= 이런것 등등도 가능하다.

-**AI를 위한 수학공부**: 오늘배운것, 기초대수학(Basic Algebra) 첫부분 시작
 - 새로 알게된 것: 
   -대수학의 특징 : Commutative Property(교환법칙), Associative Property(결합법칙), Distributive Property(분배법칙)
    - comutative property 등은 향후 행렬, 벡터 메트릭스등 여러 분야에서 계속 등장하니 개념 잘 알자.(단순히 순서 바꿔서 계산 가능하다 이상의 의미 있음.)
   -Identities and Inverses : 항등원과 역원
    - Identities 는 어떤 값과 어떤 연산을 했을때, 원래의 값과 동일하게 만드는 값.
    - Inverses 는 어떤값과 어떤 연산을 한 결과, Identities 가 나오는 값.
    - 덧셈의 Identities 는 0, Inverses 는 -a
    - 곱셈의 Identities 는 1, Inverses 는 1/a (단, a != 0)
    - 공부하면서 든 생각 : 행렬에서 단위행렬은 Identities 가 아닐까란, 그리고 역행렬은 Inverses가 아닐까란 생각이듬.

-**코딩테스트 연습**
 - 프로그래머스 레벨 0 단계 10문제.

---
## 2025 - 09 - 05 (금)
- **python study** : 편차의 제곱, 분산(+제평평제), 표준편차, 손실함수 중 Squared Error, Mean Squared Error, 데이터 전처리 -> Mean subtraction, Standardization
 -if data set:
   - score1, score2, score3 = 10, 20, 30
   - n_students = 3
   - score_mean = (score1 + score2 + score3) / n_students
   - squared_diff1 = (score1 - score_mean)**2
   - score_var = (squared_diff1 + squared_diff2 + squared_diff3) / n_students
   - 제평평제
      - mean_of_squared = (score1**2 + score2**2 + score3**2) / n_students
      - squared_of_mean = (score_mean)**2
      - score_var = mean_of_squared - squared_of_mean
   -score_std = (score_var)**0.5
   -Squared Error
    - if data set : pred1, pred2, pred3 = 10, 20, 30 / label1, label2, label3 = 5, 10, 15 / n_data
    - squared_error1 = (pred1 - label1)**2
   -Mean Squared Error(MSE): mse = (squared_error1 + squared_error2 + squared_error3) / n_data
   - 데이터 전처리
    - 딥러닝에서 모델 학습을 위해 데이터를 전처리 해주면 학습에 더 용이한데, 그를 위한 방법으로 평균은 0 으로 표준편차는 1로 만드는 Standardization을 해주면 좋다!
    - Mean Straction : 각각의 데이터 값에 평균 만큼 빼주는것
    - Standardization : 각각의 데이터 값에 평균 만큼 빼주고 표준편차로 나누어주는 것
      
    - score1 = (score1 - score_mean) / score_std
      
    - score_mean_after = (score1 + score2 + score3) / n_students -> 0
    - score_std_after = ((score1**2 + score2**2 + score3**2) / n_students - ((score1**2 + score2**2 + score3**2)/n_students)**2)**0.5 -> 1
    - 이렇게 만들어 두면 모델 학습에 좋고, 학습도 빠르다?!

-**오늘의 느낀점**
 - 공대형아(신경식) 선생님 강의를 듣는데, 코딩 같은거 10번씩 치고 다음강의 들으라는거.. 빡세다. 어떤 면에서 도움이 되는지는 이해해서 반복 훈련 중인데, 문제는 40분짜리 강의 하나 듣는데 심할때는 2~3시간 이상 걸렸음. 
 - 10번 치는걸 줄여야 하나? 음.. 조급해하지 않는 것도 중요하지만, ms ai school 전에 파이썬 레벨3 강의까진는 끝내고 싶은데, 수학도 기초대수학 끝내고 미적분 들어가고 싶고. 남은 시간이 10일이라.. 음.. 할수있는데 까지 해보자
 - 코딩에서 오류가 나는 대부분의 상황은 오타였음.. 오타가 생각보다 많이 발생(특히 강의 듣는 후반부 멍때릴때.) 그리고 노트북 키보드 생각보다 불편하다는 것도 꺠달음. 개발자한테는 키보드도 중요하려나? 특히 shift와 함께 +키나 {} 같은 중괄호 "" 같은 따음표 치는게.. 아주 뭐같음 이거때문에 시간 더 걸리는듯..




