# breast-cancer-using-MAMOGRAM-USING-INCEPTION-V3
This repository contains the code and notebook (ronda.ipynb) for Breast Cancer Detection using Mammogram Classification.
We trained a deep learning pipeline with InceptionV3 on the INbreast dataset, using advanced augmentation and explainability techniques.

🚀 Features

Transfer Learning with InceptionV3

AdamW Optimizer + LR Scheduling

Focal Loss with Class Weights

Early Stopping + Best Model Checkpointing

Evaluation Metrics: Confusion Matrix, Precision, Recall, F1-score, ROC-AUC

Grad-CAM Visualizations for explainability

Test-Time Augmentation (TTA)

📊 Results

Accuracy: ~97%

F1 Score: 0.97

ROC-AUC: 0.99

Confusion Matrix:

[[61   1]
 [ 3  59]]

📂 Files in this Repo

ronda.ipynb → Jupyter notebook with full pipeline (training + evaluation + Grad-CAM).

requirements.txt → List of dependencies.

README.md → Project documentation (this file).

📂 Dataset

Dataset: INbreast mammography dataset.

Augmented using Albumentations (70× expansion).



# Clone the repo
git clone https://github.com/yourusername/breast-cancer-detection.git
cd breast-cancer-detection

# Install dependencies
pip install -r requirements.txt
jupyter notebook ronda.ipynb


1. Training
jupyter notebook ronda.ipynb


Run all cells to train the model.
Best model will be saved automatically.

2. Evaluation

Confusion Matrix

Classification Report

ROC Curve

Grad-CAM heatmaps

🔍 Example Grad-CAM Output

(Insert a Grad-CAM image here for clarity)

📌 Future Improvements

Multi-class lesion classification.

Model ensembling (e.g., ResNet + EfficientNet).

Deploying with Streamlit or Flask.
