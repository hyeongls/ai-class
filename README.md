# ai-class

###  1. 인공지능에서 지능에 해당하는 기술은 무엇인가?

###  2. 인공지능의 종류 3가지에 대해서 설명하시오(지도학습, 비지도학습, 강화학습)
지도학습 : 레이블이 있는 데이터로 학습  <br/>
반지도학습: 레이블이 없는 데이터로 학습  <br/>
강화학습: 환경과 정책을 세움으로서 보상으로 학습  <br/>

###  3.전통적인 프로그래밍 방법과 인공지능 프로그램의 차이점은 무엇인가?

###  4.딥러닝과 머신러닝의 차이점은 무엇인가?
딥러닝: 모델 내에서 자체적으로 특징을 추출하는 인공지능(특성을 추출해서 넣어주면 성능이 더 좋아지긴 함) <br/>
머신러닝: 특징을 추출해서 모델에 넣어줘야하는 인공지능 <br/>

###  5.Classification과 Regression의 주된 차이점은?
분류: 이산적인 값을 예측하기 위해 사용, 그래프의 구역을 나누기 위해 사용 예) 성별 <br/>
회귀: 연속적인 값을 예측하기 위해 사용, 그래프의 추선을 구하기 위해 사용 예) 온도 <br/>

###  6.머신러닝에서 차원의 저주(curse of dimensionality)란?
차원이 커질수록 계산이 어려워 과적합 확률이 올라감 <br/>
차원의 저주를 해결하기 위해서는 특징의 개수를 줄임(규제 예) n1, n2, scaling) <br/>

###  7.Dimensionality Reduction는 왜 필요한가?

###  8.Ridge와 Lasso의 공통점과 차이점? (Regularization, 규제 , Scaling)

###  9.Overfitting vs. Underfitting
과적합: 과도하게 학습됨. *노이즈, 이상치, 결측치까지 학습을 했을 경우 <br/>
  해결법: 모델 단순화, 데이터 규제 <br/>
과소적합: 데이터 사이의 의존성을 잡아내지 못했을 경우 (모델이 너무 단순한 경우) <br/>
  해결법: 데이터 수 늘려줌 <br/>
  
###  10.Feature Engineering과 Feature Selection의 차이점은?

###  11.전처리(Preprocessing)의 목적과 방법? (노이즈, 이상치, 결측치)

###  12.EDA(Explorary Data Analysis)란? 데이터의 특성 파악(분포, 상관관계)

###  13.회귀에서 절편과 기울기가 의미하는 바는? 딥러닝과 어떻게 연관되는가?

###  14.Activation function 함수를 사용하는 이유? Softmax, Sigmoid 함수의 차이는?

###  15.Forward propagation, Backward propagation이란?

###  16.손실함수란 무엇인가? 가장 많이 사용하는 손실함수 4가지 종류는?

###  17.옵티마이저(optimizer)란 무엇일까? 옵티마이저와 손실함수의 차이점은?

###  18.경사하강법 의미는? (확률적 경사하강법, 배치 경사하강법, 미치 배치경사하강법)

###  19.교차검증, K-fold 교차검증의 의미와 차이

###  20.하이퍼파라미터 튜닝이란 무엇인가?

###  21.CNN의 합성곱의 역활은?

###  22.CNN의 풀링층의 역활은?

###  23.CNN의 Dense Layer의 역활은?

###  24.CNN의 stride, filter의 역활? 필터의 가중치는 어떻게 결정되는가?

###  25.RNN을 사용하는 이유와 한계점은?

###  26.STM을 사용하는 이유와 한계점은?

###  27.GRU을 사용하는 이유와 차별성은?

###  28.결정트리에서 불순도(Impurity) – 지니 계수(Gini Index)란 무엇인가?

###  29.앙상블이란 무엇인가?

###  30.부트 스트랩핑(bootstraping)이란 무엇인가?

###  31.배깅(Bagging)이란 무엇인가?

###  32.주성분 분석(PCA) 이란 무엇인가?

###  33.Dense Layer란 무엇인가?

#  -------------------------------------------------
#  1주차 정리

##  딥러닝에서 중요한 것

1. lossfunction : 정답과 예측값의 차이를 확인하는 함수 <br/>
2. optimizer : 가중치를 구하는 것 <br/>
3. backpropagation : 최적화를 위해 다시 돌아오며 계산하는 것 <br/>
4. forwardpropagation <br/>
5. activation function : 신경망에 비선형성을 추가하여 특성 추출을 더 많이 할 수 있도록 하는 방법 예) sigmoid, relu <br/><br/>

7. one-hot encodnig : 의미없는 연관성을 끊어주기 위해 사용 <br/>
