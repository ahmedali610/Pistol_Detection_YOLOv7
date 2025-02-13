# Pistol Detection using YOLOv7

## Overview
This project implements a deep learning-based pistol detection system using YOLOv7. It includes model training, inference, and evaluation, along with visualization of detection results.

## Features
- **YOLOv7-based detection**: Efficient real-time pistol detection.
- **Training and inference**: Scripts for model training and testing.
- **Evaluation metrics**: Performance analysis using precision, recall, and mAP.
- **Visualization**: Detection examples and evaluation plots.

## Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Pistol_Detection_YOLOv7.git
   cd Pistol_Detection_YOLOv7
   ```
## Usage
### Training the Model
Run the following command to train the YOLOv7 model:
```bash
python /content/yolov7/train.py --device 0 --batch-size 32 --epochs 10 --img 256 256 --data /content/data.yaml --cfg /content/yolov7/cfg/training/custom_yolov7x.yaml --weights /content/yolov7/yolov7x.pt --name yolov7 --cache
```

### Inference
To test the model on an image:
```bash
!python /content/drive/MyDrive/TheCodingBug/yolov7/detect.py --weights "/content/drive/MyDrive/Pistol detection/yolov7_model.pth" --conf-thres 0.5 --img-size 256 --source "/content/drive/MyDrive/Pistol detection/data/test/images"
```

## Results
Evaluation plots demonstrating the model performance:

### Precision Curve
![download (2)](https://github.com/user-attachments/assets/76c94460-cf23-4132-8311-0ff7579741b9)


### Recall Curve
![download (3)](https://github.com/user-attachments/assets/3b34dc66-b1dd-47c8-8295-e78b3fa089c5)

### mAP Score
![download (4)](https://github.com/user-attachments/assets/3fa72dd0-48e2-4711-9f71-d90a327cbb66)


### Detection Samples
![download (6)](https://github.com/user-attachments/assets/d53bafa4-811c-408f-b844-83d0bf1369c8)
![download (5)](https://github.com/user-attachments/assets/84c586a6-149b-4bcd-9a68-14552f25bf61)



