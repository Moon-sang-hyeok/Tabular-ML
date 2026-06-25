# Deep Architectures for Tabular Data

## Deep neural networks
- MLP-based Architectures
- Attention-based architectures

## Tree-based Models Are Still Strong
- 뉴런 네트워크가 너무 스무스한 결과를 내뱉는다 -> 특정 어떤 값이 바뀌었을 때 값이 딱 바뀌어야 되는데 반영하지 못함
- 중요하지 않은 정보를 뉴런 네트워크가 반영을 하게 돼서 성능에 영향을 미친다거나
- 똑같은 데이터로 인식(소득, 나이) -> 특징의 의미를 사용하지 못함

## Then, Why Deep Learning?
- Learnable Representations
  - representations을 학습 할 수 있음
  - 예측에 쓰이는 것 뿐아니라 다양한 곳에 활용할 수 있음
- End-to-end Feature Interactions
- Extensibility Beyond Standard Prediction
  - 텍스트나 이미지 같은 도메인도 사용할 수 있음

## 논문 2
- embedding도 어떻게 하냐에 따라 중요하다
- feature의 특징을 잘 담아서 embedding에 담아야한다

## 논문 3(MLP를 좀 더 잘 학습해보자)
- 정말로 MLP가 Tabular Data에서 안 좋은 아키텍쳐냐
- MLP만 써도 우리가 엔지니어링만 잘하면 충분히 잘 쓸 수 있다
- Preprocessing을 더 잘하고 Numerical Representation 등등 여러가지를 잘하면 충분히 잘할 수 있는 모델이다
- RealMLP

## 논문 4(Nearest Neighbors를 잘 이용해보자)
