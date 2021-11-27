# TensorFlow-Tutorial

## 전이 학습으로 이미지 분류
#### https://www.tensorflow.org/hub/tutorials/image_feature_vector?hl=ko

## 설정
### 가상환경에서 TensorFlow 설치
#### 아나콘다 프롬프트 
#### pip install --upgrade tensorflow

### 설치 확인 
#### python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"

### tensorflow_hub 설치
#### pip install --upgrade tensorflow-hub


### 기존 튜토리얼 코드에선
#### label = dirname.split('/')[-1]
### label 에러시 
#### label = dirname.split('\\')[-1]  로 수정.
####  "\\"
