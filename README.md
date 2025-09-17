<div align="center">
  <h1 align="center">UAV Detection Model Training With Custom Dataset and YOLOv8</h1>
  <h3>Open-source custom dataset with UAV-to-UAV images</h3>

  <a target="_blank" href="https://universe.roboflow.com/py-py-nu9e5/uav-detection-ovfin">
    <img src="https://github.com/roboflow/roboflow-python/assets/37276661/528ed065-d5ac-4f9a-942e-0d211b8d97de" alt="UAV Dataset" style="width:100%;height:100%">
  </a>
</div>

<div align="center">
  <a href="https://universe.roboflow.com/py-py-nu9e5/uav-detection-ovfin">📂 UAV Detection Dataset</a>
</div>

<br/>

<div align="center">
  <a href="https://github.com/Alperen012/GTU-GOLGE_Yolov8_Training/stargazers">
    <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/Alperen012/GTU-GOLGE_Yolov8_Training">
  </a>
</div>

---

## 🚀 Project Overview

This repository contains training scripts, configurations, and resources for **UAV detection using YOLOv8** with a **custom UAV-to-UAV dataset**.  

The goal of this project is to train robust UAV detection models that can be deployed in real-time aerial systems.

---

## 📌 Features

- **Custom UAV Dataset** – Collected UAV-to-UAV images for accurate detection.  
- **YOLOv8 Integration** – Cutting-edge object detection framework from [Ultralytics](https://github.com/ultralytics/ultralytics).  
- **Training & Evaluation** – Easy-to-use scripts for training, validation, and inference.  
- **Open-Source** – Contribute and improve the detection performance together!  

---

## 🛠️ Tech Stack

- [YOLOv8](https://github.com/ultralytics/ultralytics) – Object detection framework  
- [PyTorch](https://pytorch.org/) – Deep learning backend  
- [Roboflow](https://roboflow.com) – Dataset hosting & preprocessing  
- [Python](https://www.python.org/) – Programming language  
- [Jupyter Notebooks](https://jupyter.org/) – Training & testing workflows  

---

## 📂 Dataset

The UAV dataset is available here:  
👉 [UAV Detection Dataset (Roboflow)](https://universe.roboflow.com/py-py-nu9e5/uav-detection-ovfin)  

---

## ⚙️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Alperen012/GTU-GOLGE_Yolov8_Training.git
cd GTU-GOLGE_Yolov8_Training
```
### 2. Install dependencies
```
We recommend using Python 3.10+ and pip:

pip install -r requirements.txt
```
### 3. Train the model
```
yolo detect train data=data.yaml model=yolov8n.pt epochs=50 imgsz=640
```
### 5. Run inference
```
yolo detect predict model=runs/detect/train/weights/best.pt source=images/
```
### 📊 Results
```
Metrics: mAP, precision, recall, and F1-score results will be tracked and updated here after experiments.

Sample predictions will be added in the results/ folder.
```
### 🤝 Contributing
```
We welcome contributions from the community!

Fork the repo

Create a new branch (feature-xyz)

Commit your changes

Push and open a Pull Request

🌟 Contributors
<a href="https://github.com/Alperen012/GTU-GOLGE_Yolov8_Training/graphs/contributors"> <img src="https://contrib.rocks/image?repo=Alperen012/GTU-GOLGE_Yolov8_Training" /> </a> ```
