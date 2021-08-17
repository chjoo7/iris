# Iris torch: 붓꽃(iris)의 multi-class 분류

- 붓꽃의 곷잎(petal)과 꽃받침(sepal)의 폭과 길이를 센티미터 단위로 측정하여 이를 setosa, versicolor, girginica 등의 3가지 종류의 품종으로 분류하는 
  모델을 pytorch 프레임워크를 통하여 분류하는 머신러닝 모델을 작성하는 예

## Iris dataset
- Iris 데이터세트는 scikit-learn 의 datasets 모듈에 포함되어 있음. load_iris 함수를 사용해서 데이터를 적재. 150개의 붓꽃 데이터를 보유