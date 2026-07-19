# 🚂 Railway Track Crack Detection using Convolutional Neural Networks (CNN)

An end-to-end **Artificial Intelligence & Machine Learning** project that automatically detects cracks in railway tracks using **Deep Learning (CNN)** and **Computer Vision**. The project includes data preprocessing, model training, evaluation, Grad-CAM visualization, and single-image inference using TensorFlow and Keras. :contentReference[oaicite:0]{index=0}

---

## 👥 Team

- **Muhammad Hammad Raza**
- **Abdul Rafay**

---

# 📌 Project Overview

Railway track inspection is traditionally performed manually, making it time-consuming, expensive, and prone to human error. This project automates the inspection process using a **Convolutional Neural Network (CNN)** capable of classifying railway track images into:

- ✅ Non Defective
- ❌ Defective

The complete pipeline includes:

- Dataset preprocessing
- Image augmentation
- CNN model development
- Model training
- Performance evaluation
- Grad-CAM visualization
- Single image prediction
- Model export for deployment

:contentReference[oaicite:1]{index=1}

---

# 🚀 Features

- Image preprocessing and normalization
- Data augmentation
- Custom CNN architecture
- Batch Normalization & Dropout
- Automatic class weighting
- Early stopping
- Learning rate scheduling
- Model checkpointing
- Accuracy & Loss visualization
- Confusion Matrix
- ROC Curve
- Classification Report
- Grad-CAM Explainability
- Single Image Prediction
- Export trained model

---

# 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PIL (Pillow)
- KaggleHub
- Google Colab

:contentReference[oaicite:2]{index=2}

---

# 📂 Dataset

Dataset used:

**Railway Track Fault Detection Dataset**

Dataset contains two classes:

- Defective
- Non Defective

The dataset is automatically downloaded using KaggleHub.

:contentReference[oaicite:3]{index=3}

---

# 🧠 Deep Learning Pipeline

## 1. Data Preparation

- Dataset download
- Train / Validation / Test split
- Image counting
- Class visualization
- Sample image visualization

---

## 2. Data Augmentation

Training images are augmented using:

- Rotation
- Width Shift
- Height Shift
- Zoom
- Horizontal Flip
- Vertical Flip
- Brightness Adjustment
- Shear Transformation

This improves model generalization.

:contentReference[oaicite:4]{index=4}

---

## 3. CNN Architecture

The custom CNN contains:

- 4 Convolution Blocks
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout Layers
- Global Average Pooling
- Fully Connected Layers
- Sigmoid Output Layer

Regularization techniques are included to reduce overfitting.

:contentReference[oaicite:5]{index=5}

---

# ⚙️ Training Configuration

| Parameter | Value |
|-----------|-------|
| Image Size | 128 × 128 |
| Batch Size | 32 |
| Epochs | 30 |
| Learning Rate | 0.001 |
| Classes | 2 |
| Optimizer | Adam |
| Loss Function | Binary Crossentropy |

:contentReference[oaicite:6]{index=6} :contentReference[oaicite:7]{index=7}

---

# 📊 Model Evaluation

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- AUC Score
- Confusion Matrix
- ROC Curve
- Classification Report

These metrics provide a comprehensive assessment of model performance.

:contentReference[oaicite:8]{index=8}

---

# 🔥 Explainable AI (Grad-CAM)

To improve model interpretability, Grad-CAM is implemented to visualize which regions of an image influenced the model's prediction.

Grad-CAM helps verify that the CNN focuses on railway cracks rather than irrelevant background features.

:contentReference[oaicite:9]{index=9}

---

# 🖼️ Single Image Prediction

The project supports prediction on an individual railway track image by displaying:

- Original image
- Predicted class
- Confidence score
- Class probabilities

:contentReference[oaicite:10]{index=10}

---

# 📁 Generated Outputs

After training, the following files are generated:

- `railway_crack_cnn_final.keras`
- `training_history.csv`
- `class_names.json`
- `training_curves.png`
- `confusion_matrix.png`
- `roc_curve.png`
- `gradcam_results.png`
- `class_distribution.png`
- `sample_images.png`
- `inference_demo.png`

:contentReference[oaicite:11]{index=11}

---

# 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/railway-track-crack-detection.git
cd railway-track-crack-detection
```

Install dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn pillow opencv-python kagglehub
```

---

# ▶️ Running the Project

1. Open the notebook in **Google Colab**.
2. Upload your `kaggle.json` API key.
3. Run all notebook cells sequentially.
4. The dataset will download automatically.
5. Train the CNN model.
6. Evaluate performance.
7. Generate Grad-CAM visualizations.
8. Save the trained model.

---

# 📈 Model Outputs

The project generates:

- Training Accuracy Curve
- Validation Accuracy Curve
- Loss Curve
- Confusion Matrix
- ROC Curve
- Grad-CAM Heatmaps
- Prediction Probabilities
- Final Saved CNN Model

---

# 🎯 Learning Outcomes

This project demonstrates practical implementation of:

- Convolutional Neural Networks (CNNs)
- Image Classification
- Computer Vision
- Data Augmentation
- Transferable Deep Learning Pipeline
- Model Evaluation Metrics
- Explainable AI (Grad-CAM)
- TensorFlow & Keras
- Deep Learning Deployment Workflow

---

# 📜 License

This project was developed for academic and educational purposes.

Feel free to use and modify it for learning, research, and non-commercial applications.

---

# ⭐ Authors

- **Muhammad Hammad Raza**
- **Abdul Rafay**

---

## 🙏 Acknowledgements

- TensorFlow
- Keras
- Google Colab
- KaggleHub
- Railway Track Fault Detection Dataset
