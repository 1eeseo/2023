# 🍃🌳 나무 생존 여부 예측

## ✏️ 분석 과정
- NaN 값을 연관성 뛰어난 피처와 확인 후 채워줌
- NaN 값을 CatboostRegressor 로 예측 후 채워줌
- 성능 측정 지표 공부
- 결측치를 다 채운 후 target 값 예측을 위해 CatboostClassifier 사용


## 분석 후기
- 결측치 다루는 법과 이진형 데이터, 수치형 데이터 마다 다른 ML 알고리즘을 사용하는지 확인
