### 기후 데이터를 이용한 미래 기후 예측과 작물 추천

(실전 빅데이터 분석 프로젝트, 2022-05-02 ~ 2022-05-19)

#### 주제

: 1988년 부터 현재까지의 기상 데이터를 학습하여 앞으로의 기후 변화를 예측하고, 그 기후에 해당되는 재배작물 추천



#### 프로젝트 수행

- 수행방법
  - 농업관측통계시스템(OASIS)에서 기후데이터`(기온, 습도, 강수량)` 크롤링
  - KAGGLE의 Crop Recommendation Dataset  `(tempreature in Celsius, relative humidity in %, rainfall in mm)` 활용 
  - 미래 기상 데이터 값 예측 모델
  - 우리나라에서 해당 작물의 선호도 및 최소 기후 환경 분석
  - 추천 작물 출력 및 시각화
- 도구
  - 시각화 툴: Flask, Follium(추천작물의 시각화)
  - 예측모델: Ensemble Learning의 Soft Voting(기온예측과 추천작물 데이터 비교)
  - 서버: MariaDB



#### 역할
- 원동찬: 데이터 수집, 모델구성, Flask
- 권기일: 데이터 수집, 간트 차트
- 김민중: 데이터 수집, 텍스트 감성 분석
- 송민성: 데이터 수집, 모델구성, Flask
- 신재웅: 데이터 수집, 모델구성, 최종 발표



#### 추진일정

: 엑셀 간트차트에 의하여 실행 예정

[  [XLGantt_v4.7.0_20210530_Release_KOR.xlsm](..\..\..\..\XLGantt_v4.7.0_20210530_Release_KOR.xlsm) ]

