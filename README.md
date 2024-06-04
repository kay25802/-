# Stock_Prediction_Team_Project :chart_with_upwards_trend:

국내 철강 산업 경제 지표 및 주가 예측 ML/DL 프로젝트


### 국내 철강 산업 경제지표 데이터 분석 / 주가예측 ML, DL 프로젝트
---
2023 국내 철강 산업 '경제지표 데이터 분석' 및 '주가 예측'을 위한 머신러닝, 딥러닝 팀 프로젝트


### 연구배경
---
산업별 주요 거시경제지표 지수를 통해 만든 이평선이 기존의 추세추종 전략에서 사용하는 주가 이평선보다 효과적일 것이라고 가정하여 연구를 진행

---

### 프로젝트 파이프라인

#### 1) Back Testing
- 재무제표, 주가 정보 크롤링
- 철강 기업 선정
- 거래 전략별 종목 구분
- 최적 가중치 이평선 계산
- 전략별 결과 도출 및 분석

#### 2) Stock & Signal Prediction
- LSTM
- Random Forest
- DL & ML 결과 비교 분석 

### 기술스택
---
<img src="https://img.shields.io/badge/Python-3766AB?style=flat-square&logo=Python&logoColor=white"/> 


### 데이터셋
---



### 분석 결과
---
#### 1) 백테스팅 결과

 * 모멘텀과 퀄리티의 차이가 있지만 공통적으로 두 조합 모두 지표 지수를 반영해서 트레이딩을 하니 수액개선이 가능
 * 국내 철강 기업들은 대체로 지표에 따라 정직하게 흘러간다고 해석

#### 2) 철강산업 주가 예측

- (국내 철강산업) 포스코와 현대제철 주가를 기준으로 진행
![image](https://github.com/kay25802/Stock_Prediction_Team_Project/assets/119282789/3613cefe-8fb5-409b-bcca-efb38cb6afbd)
* LSTM을 사용하여 주가를 예측한 결과 거의 일치하는 주가 예측 그래프가 그려지는 것을 확인
* RF 사용 예측 수익률

