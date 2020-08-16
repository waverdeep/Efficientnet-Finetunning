# Efficientnet-Finetunning
Efficientnet을 활용하여 Finetunning 코드를 작성한다.

## 코드 구성
- train, test, val 데이터셋을 준비하여야 함
- 해당 코드에서는 train, val 소스코드만 존재함
- train과 test, val은 코드상으로 구별핮 않고 디렉토리 상으로 구별하여야 함
- Loss function : CrossEntropy
- optimizer : Adam
- Deeplearnig framework : Pytorch
- 해당 코드는 learning rate scheduler가 적용되어 있음. 만약 사용하지 않으면 해당 소스코드를 주석 처리하면 됨
