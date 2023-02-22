# Financial Data Analysis

## Lecture 3

\- 주가 그래프는 Linear 또는 Log 그래프로 나타내진다.<br/>
\- 일반적으로 주식시장의 주가 그래프는 Linear그래프로 나타나진다.<br/>
\- 하지만, Log 그래프로 표현하면 증가 폭을 주가와 상관없이 보여진다.<br/>
\- 따라서, 수익률 또는 변화율에 관심이 있다면 로그 스케일로 보는 것이 정확하다.<br/>

### Simple Returns vs Log Returns

\- 포트폴리오 관련 계산을 할 때에는 Simple Returns를 사용해야한다.<br/>
\- 왜냐하면, 포트폴리오의 수익률은 개별 자산 혹은 개별 주식의 수익률에 Weight 곱에 전체 합이 된다.<br/>
\- Weighted Average를 계산하는 경우에는 Simple Return의 Weighted Average가 포트폴리오의 Simple Return이 된다.<br/>
\- 하지만, Log Return의 Weighted Average는 포트폴리오의 Log Return이 되지 않는다.<br/>

### Frequency
수익률을 계산할 때 Daily, Weekly, Monthly 차트 중 어떤 것을 사용할지에 대한 것<br/>

\- Monthly: 일반적으로 Long-term 분석(장기 투자)을 할 때<br/>
\- Weekly: 1년 혹은 5년<br/>
\- Daily: 1년 이하<br/>

#### Frequency를 정하는 요인 중 하나는 데이터 개수이다.

\- 예를들어, 3달 정도를 투자한다고하면 Daily는 대략 60개의 데이터, Weekly는 훨씬 줄어든 데이터를 갖기 때문에 Daily 데이터를 사용하게 될 것이다.

#### 고려하는 자산의 개수가 많아지면 더 많은 데이터가 필요하다.

\- 예를들어, 100개의 주식을 가지고 포트폴리오를 구성한다면, 과거 수익률 데이터가 적어도 100개 이상은 있어야한다.<br/>
\- 하지만, Monthly 데이터만 가지고 한다면 10년 이상의 데이터가 필요하다.<br/>
\- 따라서, Daily 데이터만 가지고 한다면 6개월 정도의 데이터만 있으면 계산이 가능하다.<br/>

#### 데이터 개수는 고려하는 주식 또는 자산의 개수에 의존을 하게된다.
