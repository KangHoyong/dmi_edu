# dmi_edu
dmi_edu code 


#### PyTorch Tensor code [1]

- [pyTorch 특징 : Define and Run / Define by Run]()


- [pyTorch 이용한 Tensor 조작](https://github.com/KangHoyong/dmi_edu/blob/master/PyTorch%20Basic/Pytorch_Tensor_Allocation.ipynb)

  - 1차원 텐서선언 , 1차원 텐서 dim, shape, size ,인덱스, 슬라이싱  / 2차원 텐서 dim , shape, size , 인덱스, 슬라이싱  / 브로드 캐스팅 실습 , 주의사항 / 텐서 랜덤 인덱스, all_zero , all_ones 
  arange, empty
  - Background : pyTorch, python 라이브러리(Numpy 개념) , [pyTorch vs Numpy 차이점](https://jfun.tistory.com/238) 

#### 선형 희귀 Linear Regression [2]

- [pytorch 구현 : Linear](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/Linear_pytorch.ipynb)

  - [optimizer.zero_grad()가 필요한 이유](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/optimizer.zero_grad()%20%ED%95%84%EC%9A%94%ED%95%9C%20%EC%9D%B4%EC%9C%A0.ipynb)
  - [torch.manual_seed()를 하는 이유](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/seed%20%EA%B3%A0%EC%A0%95%ED%95%98%EB%8A%94%20%EC%9D%B4%EC%9C%A0.ipynb)

- [자동미분 pytorch 기능](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/autograd.ipynb)

- [다중 선형 희귀 Multivariable Linear regression](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/%EB%8B%A4%EC%A4%91%EC%84%A0%ED%98%95%ED%9D%AC%EA%B7%80.ipynb)

- [데이터 로더,Data Load](https://github.com/KangHoyong/dmi_edu/blob/master/Linear_Regression/DataLoad.ipynb)

#### 이진 분류 

- [시그모이드_시각화_code]()
 
- [파이토치 nn.Linear 와 nn.Sigmoid]()

- [파이토치로 구현하는 로지스틱회귀 code]()

- [로지스틱회귀 class 버전 code]()

- [로지스틱 모델(붓꽃) 데이터 활용]()


#### 선택 분류

- [소프트맥스회귀 구현]()

- [파이토치 소프트맥스 비용함수 구하기]()


#### 퍼셉트론 관련 코드
- [단층 퍼셉트론 이용하면 AND NAND OR 게이트를 구현](https://github.com/KangHoyong/dmi_edu/blob/master/Perceptron_%ED%8D%BC%EC%85%89%ED%8A%B8%EB%A1%A0(Single%20%2C%20MLP)/Single-Layer%20Perceptron_1.ipynb)

- [다층 퍼셉트론을 이용한 XOR_gate 구현](https://github.com/KangHoyong/dmi_edu/blob/master/Perceptron_%ED%8D%BC%EC%85%89%ED%8A%B8%EB%A1%A0(Single%20%2C%20MLP)/MultiLayer_Perceptron(MLP).ipynb)

- [파이토치로 다층 퍼셉트론 구현하기](https://github.com/KangHoyong/dmi_edu/blob/master/Perceptron_퍼셉트론(Single%20%2C%20MLP)/torch_MLP_XOR.ipynb)

  - Background : Linear , Sigmoid , optimizer(의미 , 종류 대표적인 SGD , adam ) 모델 정의 , Cuda , loss fn 설명 

- [사이킷런 패키지에서 제공하는 분류용 예제 데이터를 이용한 다층 퍼셉트론으로 손글씨 분류하기](https://github.com/KangHoyong/dmi_edu/blob/master/Perceptron_퍼셉트론(Single%20%2C%20MLP)/Multilayer%20Perceptron_final_code(데이터가져오기%2C%20데이터%20확인%2C%20라벨확인%2C%20모델%20생성%20%2C%20train).ipynb)

  - Background : sklearn 라이브러리 , zip(python), 모델 정의 , loss fn 설명 
