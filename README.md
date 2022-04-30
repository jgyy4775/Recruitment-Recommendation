# Recruitment-Recommendation

## Introduction
* Programmers 채용 공고 페이지를 방문한 개발자들의 방문/지원 기록을 바탕으로 추천하는 모델 구현
* 구체적으로 개발자와 채용 공고를 보고, 개발자가 해당 채용 공고에 지원할지 안 할지를 예측하는 Binary Classifier를 구현


## Dataset
* [프로그래머스 채용공고추천](https://programmers.co.kr/skill_check_assignments/1)
* 과제 응시 후 다운 받을 수 있습니다.


## Setting Environment
* Python=3.7
* Pytorch=1.10
* Numpy=1.19.5
* Scikit-learn=1.0.1
* Pandas


## Method
* Random Forest [Code](https://github.com/jgyy4775/Recruitment-Recommendation/tree/main/using_randomforest)
* Logistic Regression [Code](https://github.com/jgyy4775/Recruitment-Recommendation/tree/main/using_ann)


## Model Evaluation
* Metrics :  Accuracy

|Random Forest|Logistic Regression|
|:-----------:|:-----------:|
|  82.3408%   |  85.4209%  |
