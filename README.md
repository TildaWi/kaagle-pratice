# 📝 Kaggle Practice

Kaggle 프로젝트를 필사하며 코드와 개념을 공부하고, 매주 하나씩 실습해 정리합니다.

---

## 📅 학습 기록

| 주차 | 날짜       | 주제                                                        |
|------|------------|--------------------------------------------------------------|
| 1주차| 2025-07-12 | Instant Gratification                                       |
| 2주차|            | IEEE-CIS Fraud Detection                                    |
| 3주차|            | Quick, Draw! Doodle Recognition                             |
| 4주차|            | Bengali.AI Handwritten Grapheme Classification              |
| 5주차|            | SIIM-ACR Pneumothorax Segmentation                          |
| 6주차|            | Jigsaw Unintended Bias in Toxicity Classification           |
| 7주차|            | Bike Sharing Demand                                         |
| 8주차|            | Seoul Bike Sharing                                          |
| 9주차|            | Store Item Demand Forecasting                               |
| 10주차|           | Inventory Demand Forecasting                                |
| 11주차|           | Uber Pickups in NYC                                         |
| 12주차|           | Delivery Time Prediction                                    |
| 13주차|           | Favorita Grocery Sales Forecasting                          |
| 14주차|           | Predict Future Sales                                        |
| 15주차|           | M5 Forecasting Accuracy                                     |
| 16주차|           | Walmart Sales Forecasting                                   |

---

## 📂 프로젝트 목록

### 1️⃣ Instant Gratification (분류)
- 📁 [`instant-gratification`](./instant-gratification)
- 목표: 예측 대회에서 빠른 피드백 기반 최적화
- 주요 내용:
  - EDA 및 데이터 정규화
  - XGBoost 모델링
  - 평가 지표: AUC

---

### 2️⃣ IEEE-CIS Fraud Detection (분류)
- 📁 [`ieee-cis-fraud`](./ieee-cis-fraud)
- 목표: 거래 데이터 기반 이상 탐지
- 주요 내용:
  - 범주형 데이터 처리
  - LightGBM 모델 적용
  - 평가 지표: ROC-AUC

---

### 3️⃣ Quick, Draw! Doodle Recognition (CNN)
- 📁 [`quickdraw-doodle`](./quickdraw-doodle)
- 목표: 손그림 데이터 분류
- 주요 내용:
  - CNN 모델 설계
  - 데이터 증강(Data Augmentation)
  - 평가 지표: Accuracy

---

### 4️⃣ Bengali Handwritten Grapheme Classification (이미지 분류)
- 📁 [`bengali-grapheme`](./bengali-grapheme)
- 목표: 손글씨 이미지에서 Grapheme 예측
- 주요 내용:
  - EfficientNet 기반 Transfer Learning
  - 평가 지표: Macro F1 Score

---

### 5️⃣ SIIM-ACR Pneumothorax Segmentation (이미지 세그멘테이션)
- 📁 [`siim-pneumothorax`](./siim-pneumothorax)
- 목표: CT 이미지에서 기흉 영역 분할
- 주요 내용:
  - U-Net 모델링
  - Dice Loss 사용

---

### 6️⃣ Jigsaw Unintended Bias in Toxicity Classification (NLP)
- 📁 [`jigsaw-toxicity`](./jigsaw-toxicity)
- 목표: 댓글 데이터에서 혐오 발언 분류
- 주요 내용:
  - LSTM + Attention Mechanism
  - 평가 지표: AUC

---

### 7️⃣ Bike Sharing Demand (회귀)
- 📁 [`bike-sharing-demand`](./bike-sharing-demand)
- 목표: 자전거 대여 수요 예측
- 주요 내용:
  - 시계열 데이터 전처리
  - RandomForest 및 XGBoost 회귀
  - 평가 지표: RMSLE

---

### 8️⃣ Seoul Bike Sharing (회귀)
- 📁 [`seoul-bike-sharing`](./seoul-bike-sharing)
- 목표: 따릉이 대여량 시간대별 예측
- 주요 내용:
  - 공휴일, 날씨 변수 Feature Engineering
  - 선형 회귀 및 LightGBM 비교
  - 평가 지표: RMSE

---

### 9️⃣ Store Item Demand Forecasting (회귀)
- 📁 [`store-item-demand`](./store-item-demand)
- 목표: 점포별 SKU 수요 예측
- 주요 내용:
  - Lag Features 및 Moving Average 적용
  - ARIMA 모델링 실습
  - 평가 지표: RMSE

---

### 1️⃣0️⃣ Inventory Demand Forecasting (회귀)
- 📁 [`inventory-demand`](./inventory-demand)
- 목표: 적정 재고량 예측
- 주요 내용:
  - KPI 지표 설계 및 적정 재고 산출 로직
  - Prophet 시계열 모델링
  - 평가 지표: MAE

---

### 1️⃣1️⃣ Uber Pickups in NYC (회귀)
- 📁 [`uber-pickups-nyc`](./uber-pickups-nyc)
- 목표: 시간대별 Uber 호출량 예측
- 주요 내용:
  - Geospatial 데이터 시각화
  - Prophet 및 XGBoost 모델 비교
  - 평가 지표: RMSE

---

### 1️⃣2️⃣ Delivery Time Prediction (회귀)
- 📁 [`delivery-time-prediction`](./delivery-time-prediction)
- 목표: 라스트마일 배송 ETA 예측
- 주요 내용:
  - 경로 및 거리 기반 Feature Engineering
  - LightGBM 및 CatBoost 모델링
  - 평가 지표: RMSLE

---

### 1️⃣3️⃣ Favorita Grocery Sales Forecasting (시계열 회귀)
- 📁 [`favorita-sales-forecasting`](./favorita-sales-forecasting)
- 목표: 에콰도르 점포·SKU별 일별 판매량 예측
- 주요 내용:
  - 시계열 데이터 다변량 분석
  - Hierarchical Forecasting 적용
  - 평가 지표: NWRMSLE

---

### 1️⃣4️⃣ Predict Future Sales (회귀)
- 📁 [`predict-future-sales`](./predict-future-sales)
- 목표: 러시아 소매점 판매량 예측
- 주요 내용:
  - Lag Feature 및 Rolling Mean 생성
  - XGBoost 및 LSTM 모델 비교
  - 평가 지표: RMSE

---

### 1️⃣5️⃣ M5 Forecasting Accuracy (시계열 회귀)
- 📁 [`m5-forecasting-accuracy`](./m5-forecasting-accuracy)
- 목표: Walmart 판매량 계층적 시계열 예측
- 주요 내용:
  - Recursive Forecasting
  - LightGBM + Prophet 조합 실험
  - 평가 지표: WRMSSE

---

### 1️⃣6️⃣ Walmart Sales Forecasting (회귀)
- 📁 [`walmart-sales-forecast`](./walmart-sales-forecast)
- 목표: Walmart 매장·카테고리별 판매량 예측
- 주요 내용:
  - 시즌성 및 공휴일 효과 반영
  - Gradient Boosting 모델링
  - 평가 지표: RMSLE

---

## ✅ 학습 규칙

1. 매주 1개 프로젝트 필사 및 분석 정리
2. 프로젝트별 `EDA`, `모델링`, `회고` 노트 작성
3. 코드 및 결과물은 Jupyter Notebook으로 관리
4. 주요 내용은 이 레포지토리의 README에 기록

---

## 📖 참고 자료 
- 캐글 메달리스트가 알려주는 캐글 노하우
