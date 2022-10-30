## Diffusion study
### Naver Boost camp T4126 염성현
- - -
### Time Line
- - -
#### 22/10/16, Diffusion study 1회차
- DDPM 논문 1회독, 논문 내용에 대한 토의 진행
- [회의록](../../%ED%9A%8C%EC%9D%98%EB%A1%9D/diffusion_1016.txt)

#### 22/10/23, Diffusion study 2회차
- [DDPM 영상 자료](https://youtu.be/_JQSMhqXw-4) 시청 후 스터디 참여
- 논문 내용 및 수식 부분에 대한 심화 토의 진행
- [회의록](../../%ED%9A%8C%EC%9D%98%EB%A1%9D/diffusion_1023.txt)
- 이후 DDPM 블로그 글 작성 시작

#### 22/10/30, Diffusion 학습
- Boostcamp project 건으로 study 연기
- [Score-based Generative models and Diffusion models 관련 영상 사전 시청](https://youtu.be/d_x92vpIWFM)
- [study 시간 동안 Diffusion model 유투브 영상 시청 및 학습](https://youtu.be/uFoGaIVHfoE)
    - Forward : Beta,t를 scheduling을 어떻게 할 지를 먼저 정의를 내려서 각각 noise를 얼만큼 입힐 지를 미리 정의를 내릴 수 있고요. 이를 통해서 X0에서 time step T의 XT를 한번에 구할 수 있다.
    - Reverse : 모델을 학습을 시켜서 각각 time step T의 Gaussian Kernel이 어떤 평균과 variance를 지니고 있는지를 학습을 하는 거고 이 평균을 수식적으로 풀어보니 epsilon에 관한 식으로 나타낼 수 있었고 이를 통해서 noise만 prediction하는 최종적인 loss term을 가지게 되었습니다.
    - DDPM, DDPM, Score-based, SDE 등에 관한 좋은 학습 자료
- 수식적인 부분에 대한 이해를 높임
- Bayesian rule, Gaussian Distribution, U-net, Markov chain, Score function 등 추가 학습 필요
