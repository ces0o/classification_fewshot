
# class 1 제거 dataset
## densenet_121
<img src="https://github.com/ces0o/image_/blob/6189f36425833bb18c879e9211332c223a7d7388/d1.png" width="400" height="100">  

<img src="https://github.com/ces0o/image_/blob/ca28bc3ba3166797106bfe8adb328db9bb79754c/densenet121(false).png" width="900" height="300">  

* 최대 accuracy: 95.14% , 최소 loss: 0.1515

## densenet_201
<img src="https://github.com/ces0o/image_/blob/8110211f9582870ebb3951334d9cf4f9d80d2af6/18.2.png" width="400" height="200">  

<img src="https://github.com/ces0o/image_/blob/9edda1c31c1327a190a746a4655ecf3b6286ce41/RRRRR.png" width="900" height="300">  

* 최대 accuracy: , 최소 loss:

## resnet_18
<img src="https://github.com/ces0o/image_/blob/add7f64cf01b33bafbba4ed825cc1ffd35dd26f4/resnnnnn.png" width="400" height="100">  

<img src="https://github.com/ces0o/image_/blob/20d453769766848fdbb46572da3e0d03bf67106c/res.png" width="900" height="300">  

* 최대 accuracy: 93.75%, 최소 loss: 0.2658

## resnet_101
<img src="https://github.com/ces0o/image_/blob/825b157dc0749773542c0688f08dd02e9c12b25f/kik.png" width="400" height="100">  

<img src="https://github.com/ces0o/image_/blob/c277f42bfa39bc9a9a3a43e4bb3ce5dbaf08909d/res101.png" width="900" height="300"> 

* 최대 accuracy: 89.92%, 최소 loss: 0.3

## EfficientNetV2-L
<img src="https://github.com/ces0o/image_/blob/c277f42bfa39bc9a9a3a43e4bb3ce5dbaf08909d/eff.png" width="400" height="100"> 

<img src="https://github.com/ces0o/image_/blob/21bf0dd71a5527390d22910bd5b2242b6ef4f104/effrres.png" width="900" height="300">  

* 최대 accuracy: , 최소 loss: (pretrain = false)

## densenet vs resnet
### Feature Reuse 및 정보 유지  
* DenseNet은 밀집 연결(dense connectivity)을 사용하여 각 레이어에서 이전 레이어의 출력을 입력으로 받음
  * 특히 임신테스트기에서 crop된 이미지의 경우 색의 차이가 미미하게 나타나기 때문에, 이러한 밀집 연결은 특징을 재사용하는 데 도움을 줄 수 있음
* ResNet은 잔차 연결(residual connection)을 사용하므로 각 레이어는 이전 레이어의 잔차만을 사용하게 됨
   * densenet보다 정보 손실이 심함
 

