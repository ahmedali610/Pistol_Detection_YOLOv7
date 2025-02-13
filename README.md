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
(![download (3)](https://github.com/user-attachments/assets/3b34dc66-b1dd-47c8-8295-e78b3fa089c5))

### mAP Score
![mAP Score](results/map_score.png)

### Detection Samples
![Detection Sample 1](results/detection1.png)
![Detection Sample 2](results/detection2.png)
![Detection Sample 3](results/detection3.png)

## License
This project is open-source under the [MIT License](LICENSE).

## Acknowledgments
- [YOLOv7 GitHub Repository](https://github.com/WongKinYiu/yolov7)
- Open-source datasets used for training and testing.

---
Feel free to modify this README to match your specific implementation!
