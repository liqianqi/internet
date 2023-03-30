# internet

## 人脸检测
- 直接使用的yolov5-face进行训练，做的改动实在head前面加上一层CoordConv，提高关键点回归能力
## 人脸识别
- 采用VGG16模型，直接获得128向量，然后在做比对