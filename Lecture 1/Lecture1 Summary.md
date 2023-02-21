# Financial Data Analysis

## Lecture 1


- Most analysis using financial data is generally based on historical data<br/>
- For example, historical price or return data of stocks<br/>
=> 금융 데이터를 사용한 분석은 일반적으로 과거 데이터를 기반으로한다.<br/>
=> 예를들어, 과거 주가 또는 과거 수익 데이터가 있다.<br/>


### \<Historical Price\>
  
- Most basic data that is produced from the stock market is the stock price<br/>
- Unless one is trading intraday, one will normally use the close price for analysis<br/>
=> 주식 시장에서 생성되는 대부분의 데이터는 주가이다.<br/>
=> 거래를 하지 않는한 일반적으로 분석을 위해 Close를 사용한다.<br/>

### \<Adjusted Close Price\>

- The adjusted closing price amends a stock's closing price to reflect that stock's value after accounting for any corporate actions(split or dividend)<br/>
- It is often used when examining historical returns or doing a detailed analysis of past performance<br/>
- The closing price is the raw price, which is just the cash value of the last transacted price before the market closes<br/>
=> Adj Close는 분할 또는 배당을 고려하여 주식 가치를 반영하기위해 주식의 종가를 수정한다.<br/>
=> 과거 수익률을 조사하거나 실적에 대한 상세한 분석을 할 때 자주 사용한다.<br/>
=> Close는 단지 주식 시장이 마감되기전 마지막 거래 가격일 뿐이다.<br/>

### \<Adjusting prices for stock splits\>

=> 주식 분할 또는 액면 분할을 하는 이유는 큰 가격에 주가가 거래될 때 사람들이 투자를 하기 쉽지 않으니 더 많은 거래를 활성화 하기 위해 액면 분할을 한다.<br/>
=> 시가 총액에는 영향을 주지 않고 거래 가격에만 영향을 준다<br/>

### \<Adjusting prices for dividends\>

- While stock prices do not directile reflect dividend payments, the dividends are still part of the investor's returns. <br/>
- By subtracting dividends from previous stock prices, we obtain the adjusted closing prices and a better picture of returns<br/>
=> 주식 배당은 주가에 직접적으로 반영되지 않지만, 배당금은 투자자 수익의 일부이다.<br/>
=> 이전 주가에서 배당금을 빼서, Adj Close를 얻을 수 있다.<br/>

### \<Kurtosis\>

- Kurtosis는 큰 것은 가운데가 높이 올라가기도 하는데 측정하는 것은 tail 부분을 본다<br/>
- Outlier가 더 많으면 Kurtosis가 더 크다<br/>

### \<Returns of Indices\>

- 보통 주식시장이 올랐다, 내렸다라고 얘기를 하면 주식 시장을 대표하는 지수가 상승 또는 하락했다고 말을 한다.<br/>
- 미국의 경우는 DOW, S&P가 있다. 우리나라는 KOSPI<br/>

### \<Index\>

- A stock index, or stock market index, is an index that measures a stock market, 
  or a subset of the stock market, that helps investors compare current price levels with past prices to calculate market performance.<br/>
- It is computed from the prices of selected stocks<br/>
=> 지수는 주식시장 또는 주식시장을 측정하는 지수로, 투자자들이 시장 성과를 계산하기 위해 현재의 가격 수준을 과거의 가격과 비교할 수 있도록 도와준다.<br/>

### \<Decision Factor of Stock Market Index\>

- The boundaries of the index's universe
 -> 바운더리를 결정해야한다(전체, 산업군 등)
- The criteria for inclusion in the index
 -> 인덱스에 포함 될 기업을 선정할 기준 혹은 정의
- How the stocks are weighted
 -> Price weighting*, Value weighting*, or equal weighting(계산 할 방법)
- How returns are calculated
 -> 배당금 같은 것을 포함할지 말지

### \<Index Weighting Choices\>

- Price-Weighted Index: 각 기업의 평균 값을 지수로 정할 때 Weight를 Price로 둔다

- Value-Weighted Index: 시가총액을 기준으로 가중 평균을 계산한다

- Float-Weighted Index: 시가총액 전체를 사용하는 것이 아닌 거래되고 있는 비중만 사용해서 시가총액과 비슷한 가치를 계산한다


