# Financial Data Analysis

## Lecture 5

### Factor Model
 \- 개별 자산의 수익률이 여러가지 요인들에 의해서 결정된다 보는 모델이다. 포트폴리오 구성, 리스크 관리, 성과 평가 등 다양한 분야에서 사용됙 있다.
 
### Factor model을 사용하는 이유
  1. Factor를 찾아서 주식이나 자산의 움직임을 설명할 수 있다.<br/>
  2. 여러 자산군에 Factor Model이 적용되고 있고, Factor-based 투자도 많이 적용되고있다.<br/>
  3. 여러가지 기법들이 적용되고 있고, 최근에는 딥러닝을 활용한 연구도 진행되고 있다.<br/>

### Introduction
1. Regression-based 모델은 포트폴리오의 예상 수익률과 위험을 예측하는데 사용된다.
2. 가중치는 Factor 민감도로 불리고 Factor beta라고 한다. 
3. Beta는 회귀분석을 통해 추정한다.

### Single Factor Models
 \- 가장 널리 알려진 Single Factor Model은 CAPM(Capital Asset Pricing Model)이다.
 
## $E(R_i) - R_f = \beta_i(E(R_M) - R_f)$


### CAPM이 중요한 이유
 \- CAPM에서 어떤 주식의 초과수익률의 기댓값은 베타로 표현된다.<br/>
 \- 포트폴리오에서 리스크는 분산 혹은 표준편차로 표현이 되는데, 개별주식의 수익률 같은 경우에는 베타로 표현이 된다.
