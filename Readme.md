# [Kaggle Challenge] What's cooking

## 0. 개요
- 주어진 recipe를 통해 11가지의 cuisine으로 분류한다.
- 개인프로젝트 (기간: 2017.08.21~2017.08.25)

## 1. 목표
- f1 score를 최대한 높인다.

## 2. Work flow

	다음과 같은 두 가지 방법으로 진행했습니다.
	첫째, tfidfVectorizer로 수치화 한 뒤 모델링
	둘째, PCA기법으로 차원을 축소한 뒤 모델링
	- 최적의 parameter를 구하기 위해 grid search를 이용했습니다.
	- KNN, SVM, Randomforest, Xgboost, Neural Network 총 6가지의 분류 모델을 사용했습니다.

## 3. 결과
tfidfVectorizer를 이용하여 데이터를 수치로 변환한 뒤, Xgboost 모델을 쓴 경우 0.778로 가장 높은 score를 기록했습니다.

## 4. URL
https://render.githubusercontent.com/view/ipynb?commit=484f5634ddfd4691519b3bfa632014a877b18ee9&enc_url=68747470733a2f2f7261772e67697468756275736572636f6e74656e742e636f6d2f596f6f6f6e6b79756e672f57686174732d436f6f6b696e672f343834663536333464646664343639313531396233626661363332303134613837376231386565392f57686174735f436f6f6b696e675f4b6167676c652d6368616c6c656e67652e6970796e62&nwo=Yooonkyung%2FWhats-Cooking&path=Whats_Cooking_Kaggle-challenge.ipynb&repository_id=100808172&repository_type=Repository#Kaggle-competition---What's-cooking