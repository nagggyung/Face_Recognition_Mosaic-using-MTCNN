## 1. Project: MTCNN Face detection model 과 Edge Device를 활용한 Realtime 인물 인식 및 자동 모자이크 시스템

* MTCNN - Face Detection
* OpenCV - Face Recognition & Mosaic
* Edge Device - Rasberry Pi4 사용

### 2. git clone MTCNN model: https://github.com/ipazc/mtcnn

### 3. Tools:
* Tensorflow 2.4
* OpenCV 

## 4. How to improve the face detection model

* ssd model 또는 yolov3 이상의 모델을 사용 - 모델이 비교적 가볍고 정확도 와 속도 측면에서 높은 성능을 보인다. 
* Facenet 사용 - 프로젝트 진행 시에 gpu 환경에서 구현을 한 것이 아니기 때문에 Facenet을 사용하지 못하였지만, Facenet을 사용하면 Face Recognition을 할때 정확도를 향상시킬 수 있다. 
* Edge Device : Jetson nano 사용 - gpu 환경에서 모델을 돌릴 수 있기 때문에 속도를 향상 시킬 수 있다.  
