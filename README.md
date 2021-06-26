<h1>Project: MTCNN Face detection model 과 Edge Device를 활용한 Realtime 인물 인식 및 자동 모자이크 시스템</h1>

MTCNN - Face Detection<br>
OpenCV - Face Recognition & Mosaic<br>
Edge Device - Rasberry Pi4 사용<br>

git clone MTCNN model: https://github.com/ipazc/mtcnn

<br>
<h2>추가적으로 성능 향상을 해야할 것들,</h2><br>
1) SSD 모델(Dataset- WIDER FACE): MTCNN 모델 보다 속도나 정확도 면에서 더 높은 성능 가짐<br>
2) FaceNet: 딥 러닝 모델을 사용하여 얼굴 인식 시 인식 정확도 향상 가능<br>
3) 모델 경량화(ex. Pruning Algorithm): 경량화 알고리즘을 통해 딥러닝 모델을 경량화 시킨다면 Edge Device 이식시 최적화 가능<br>
4) Jetson Nano: Edge Device로 GPU 탑재된 Jetson Nano 사용 시 성능 향상 가능<br>


