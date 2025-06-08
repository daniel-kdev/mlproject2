# mlproject2
[은행계좌를 유지할지 폐지할지를 예측](https://www.kaggle.com/competitions/playground-series-s4e1) 하기 위해서 Logistic Regression, Random Forest, LDA, QDA, XGBoost, SVM 모델을 사용하여 예측의 정확성을 평가하였다.

케클에서 제공한 데이터의 특성을 살표보기 위해서 교수님이 준 코드를 사용하였다. 
이 코드를 활용하여 범주형 변수와 수치형 변수를 구분하였다. 

데이터를 읽어들이 후에 범주형 변수들을 One Hot Enconding 방식을 이용하여 수치형 변수로 변경하였다. 

train_data를 8:2의 비율로 학습셋과 테스트셋으로 구분하였다. 
train_data의 학습셋을 이용하여 모델을 학습하고, 테스트 셋으로 예측의 정확성을 평가하하고, ROC 그래프를 작성하였다. 
모든 모델에 대하여 동일한 형태로 학습하고 평가하였다. 그리고, ROC그래프는 누적형태로 그렸다.

SVM모델의 경우는 다른 모델에 비하여 수행시간이 매우 길었다. 

mlproject2.ipynb는 변수들을 스케일일링하지 않고 위 과정을 적용한 코드이다. 
mlporject2-scaled.ipynb는 변수들을 스케일링한후에 위 과정을 적용한 코드이다. 


