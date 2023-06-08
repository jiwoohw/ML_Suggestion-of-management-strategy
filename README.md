# 💡📑 [ML]Suggestion-of-management-strategy 📑💡
 Sales forecasting and RFM analysis using kaggle olist data  </br>
 프로젝트 기간 : 2023.5.3 - 2023.5.26
 </br>

## 1️⃣ 프로젝트 주제
- e-commerce 매출 예측 & 고객 세분화 </br>
 </br>
-> 매출 예측을 통한 매출 전략 제시, 의사결정에 도움 </br>
-> 고객 세분화를 통한 고객 맞춤 마케팅

</br>

## 2️⃣ 주제 선정 이유
- 코로나19이후 E-commerce 성장 가속화
- 브라질 e-commerce 성장

<img width="565" alt="image" src="https://github.com/jiwoohw/ML_Suggestion-of-management-strategy/assets/122995812/90e0e52f-5492-4fb3-ad07-c8b7c2e580a1"> </br>
출처 : http://energia.mofa.go.kr/WZ/WZ_211/html/special_report3.html

</br>

## 3️⃣ 데이터
- kaggle data 
- Brazilian E-Commerce Public Dataset by Olist
- 100,000 Orders with product, customer and reviews info
 ![image](https://github.com/jiwoohw/ML_Suggestion-of-management-strategy/assets/122995812/548477cf-1ccb-4f69-afc6-8463a88f5910)

</br>

## 4️⃣ EDA
: 고객, 상품, 주문, 금액, 판매, 리뷰, 배송 분석



</br>

## 5️⃣ 매출 예측
- ADF검정으로 데이터 정상성 확인 </br>
 -> 차분하고 정상성 확인 </br>
  </br>
- 8주동안 매출 학습하여 그 이후 1주 예측 </br>
1) Machine Learning  </br>
   : XGB
2) Deep Learning  </br>
   : LSTM

- RMSE 기준 성능이 가장 좋은 LSTM으로 다음 주 매출 예측 
![image](https://github.com/jiwoohw/ML_Suggestion-of-management-strategy/assets/122995812/3b2bb200-a2fd-4ca9-9eb4-1f5037c5fda0)
</br>

## 6️⃣ RFM
1) 가중치 부여하지 않고 rfm score생성
2) 각 컬럼 outlier 제거
3) rfm_score으로 segmentation 진행
4) olist 고객 segmentation 비중 확인 후, 고객 등급화
![image](https://github.com/jiwoohw/ML_Suggestion-of-management-strategy/assets/122995812/526414c8-a1d1-4417-a1c6-f83f90259e8a)


</br>

## 7️⃣ 기대효과

- 상품매출을 예상하여 매출전략 제시
- RFM으로 고객 세분화하여 고객에게 맞춤 타겟팅 기대

---
</br>

