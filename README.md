# Pistol Detection using YOLOv7

## Overview
This project implements a deep learning-based pistol detection system using YOLOv7. It includes model training, inference, and evaluation, along with visualization of detection results.

## Features
- **YOLOv7-based detection**: Efficient real-time pistol detection.
- **Training and inference**: Scripts for model training and testing.
- **Evaluation metrics**: Performance analysis using precision, recall, and mAP.
- **Visualization**: Detection examples and evaluation plots.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Pistol_Detection_YOLOv7.git
   cd Pistol_Detection_YOLOv7
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Training the Model
Run the following command to train the YOLOv7 model:
```bash
python train.py --dataset /path/to/dataset --epochs 50
```

### Inference
To test the model on an image:
```bash
python detect.py --source image.jpg --weights best.pt
```

### Evaluation
Run evaluation to generate performance metrics:
```bash
python evaluate.py --weights best.pt
```

## Results
Evaluation plots demonstrating the model performance:

### Precision-Recall Curve
![Precision-Recall Curve](results/precision_recall.png)

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
