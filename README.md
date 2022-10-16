# HYU-DeepLearning
딥러닝 수업 과제로 모델을 직접 구현해보았습니다.

## 구현 언어 및 도구
- Python
- VS Code
- Jupyter Notebook

## 목차
1. [Logistic Regression](https://github.com/happyhun/HYU-DeepLearning/tree/main/LogisticRegression)
2. [Neural Network 2-layer](https://github.com/happyhun/HYU-DeepLearning/tree/main/2-LayerNeuralNetwork)

## 이슈
[Neural Network 2-layer](https://github.com/happyhun/HYU-DeepLearning/tree/main/2-LayerNeuralNetwork) 01번 문제를 해결할 때, accuracy가 60대로 계속해서 낮게 나오는 문제가 있었다.  
  
원인은 sigmoid함수에 들어가는 입력값이 조금만 커져도 전부 1로 처리가 되어서 학습이 제대로 되지 않기 때문이었다.  
  
그래서 W, b를 초기화할 때 랜덤하게 하지 않고 초기 입력값이 작아지도록 만드니 학습이 잘 되었다.
