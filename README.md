Pistol Detection using YOLOv7

Overview

This project implements a deep learning-based pistol detection system using YOLOv7. It includes model training, inference, and evaluation, along with visualization of detection results.

Features

YOLOv7-based detection: Efficient real-time pistol detection.

Training and inference: Scripts for model training and testing.

Evaluation metrics: Performance analysis using precision, recall, and mAP.

Visualization: Detection examples and evaluation plots.

Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/Pistol_Detection_YOLOv7.git
cd Pistol_Detection_YOLOv7

Install dependencies:

pip install -r requirements.txt

Usage

Training the Model

Run the following command to train the YOLOv7 model:

python train.py --dataset /path/to/dataset --epochs 50

Inference

To test the model on an image:

python detect.py --source image.jpg --weights best.pt

Evaluation

Run evaluation to generate performance metrics:

python evaluate.py --weights best.pt

Results

Evaluation plots demonstrating the model performance:

Precision-Recall Curve



mAP Score



Detection Samples





License

This project is open-source under the MIT License.

Acknowledgments

YOLOv7 GitHub Repository

Open-source datasets used for training and testing.
