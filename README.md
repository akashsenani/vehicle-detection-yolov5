# 🚗 Vehicle Detection Using YOLOv5

This project implements a real-time vehicle detection system using the YOLOv5 deep learning framework. It trains a custom object detection model on annotated vehicle images and evaluates its performance using precision-recall curves, F1 scores, and confusion matrices.

---

## 🔍 Key Features

- Custom YOLOv5 training on vehicle dataset
- High-accuracy real-time detection
- Evaluation metrics: Precision, Recall, F1, mAP
- Visualizations: PR curves, Confusion Matrix, Label distribution
- Simple inference script for testing on custom images
- Organized repository for reproducibility and collaboration

---

## 📁 Repository Structure

```

vehicle-detection-yolov5/
├── weights/              # Trained YOLOv5 model (best.pt)
├── data/                 # Data configuration (data.yaml)
├── images/               # Visualizations and dataset previews
├── inference/            # Inference script and test image
├── utils/                # Optional helper scripts
├── README.md             # Project overview and instructions
└── requirements.txt      # Required Python libraries

````

---

## 📊 Results and Visualizations

### 🔹 Precision-Recall and F1 Score Curves

| Precision | Recall | PR Curve | F1 Score |
|----------|--------|----------|----------|
| ![BoxP](images/BoxP_curve.png) | ![BoxR](images/BoxR_curve.png) | ![BoxPR](images/BoxPR_curve.png) | ![BoxF1](images/BoxF1_curve.png) |

### 🔹 Confusion Matrices

| Raw Confusion Matrix | Normalized Confusion Matrix |
|----------------------|-----------------------------|
| ![Confusion Matrix](images/confusion_matrix.png) | ![Normalized Confusion Matrix](images/confusion_matrix_normalized.png) |

### 🔹 Dataset Labels and Batches

| Label Distribution | Training Batch | Validation Batch |
|--------------------|----------------|------------------|
| ![Labels](images/labels.jpg) | ![Train](images/train_batch0.jpg) | ![Val](images/val_batch0_labels.jpg) |

---

## 📦 Model Weights

Trained YOLOv5 weights are included under:

```
weights/best.pt
```

---

## 📌 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🤝 Contribution

Pull requests are welcome. For major changes, open an issue first to discuss what you would like to change.

---
