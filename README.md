# YOLOv5-x
YOLOv5-x 커스텀 객체 인식 모델 구현
#### 개발자
------------------------
이수진 - Soojin-Lee-01
#### 개발환경
------------------------
YOLOv5-x, Linux, Python, Pycharm
#### 데이터 소개
------------------------
칸쵸, 참깨스틱, 음료수 캔, 감자깡, 고구마깡, 포스틱, 새우탕, 진라면, 프링글스, 튀김우동
#### 사용 모델
------------------------
YOLOv5-x model
+ YOLOv5란?
  + You Only Look Once의 약자로 Object Detection 분야에 많이 알려진 모델, 실시간으로 Object Detection이 가능하도록 만들었다.
+ YOLOv5 특징
  + 실시간으로 객체를 탐지
  + 이미지 전체를 한번만 봄
  + 통합된 모델을 사용
+ YOLOV5 구조
  + 백본 (Backbone) : 입력이미지를 feature map으로 변형
  + 헤드 (Head) : 백본에서 추출한 feature map의 location 작업을 해주는 부분, predict classes와 bounding boxes 작업이 수행
  + 넥 (Neck) : 백본과 헤드를 연결하는 부분, feature map을 정제하고 재구성
+ YOLOv5 모델의 종류
  + YOLOv5s (small), YOLOv5m (medium), YOLOv5l (large), YOLOv5x (xlarge)
  + ![스크린샷 2024-05-21 152738](https://github.com/DuksungElectronics/YOLOv5-x/assets/87466284/1a1a0fae-b1c9-4046-9716-d69f59145ed6)
  + ![스크린샷 2024-05-21 152751](https://github.com/DuksungElectronics/YOLOv5-x/assets/87466284/45cd8c11-42c4-469b-ab75-ef1442977cf7)
    + 출처 : https://github.com/ultralytics/yolov5
#### 훈련 및 결과
+ 훈련 parameter
  + batch size :
  + epochs : 
  + lr : 
+ 훈련 환경
  + 2 way GPU, Linux
+ 결과
  + Confusion matrix
     
  
