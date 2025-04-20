# 🚨 Flood Detection/Segmentation Model using YOLOv11
This repository contains object detection models trained to detect flood using YOLOv11.

### 🧠 Model Descriptions
- **custom.pt**: A custom YOLOv11-based model trained on 12,463 labeled images (flood).
- **yolov11n.pt**: A pre-trained YOLOv11 nano model trained on the COCO dataset. Lightweight and optimized for general-purpose object detection with high inference speed, but not tailored for disaster-specific scenarios.

## Data Balance Summary
---------------------------------------------------------
Collision
📊 Dataset Split Summary
train data: 9970
validation data: 2493
🧮 Total: 12,463 images

## 🎥 Detection Demo
<p align="center">
  <img src="1-flood-demo" width="100%"/>
</p>