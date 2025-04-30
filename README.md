#🧪 Liver Damage Detection from Histopathological Images
🔍 Overview
This project uses deep learning to detect liver damage by classifying histopathological tissue images into three categories:

Cholangiocarcinoma

Hepatocellular Carcinoma (HCC)

Normal Liver

🧠 Key Features
Trained and evaluated three powerful models: ConvNeXtV2, EfficientViT-B2, and SwinV2.

Automatic hyperparameter tuning using Optuna.

Clean, lab-themed Streamlit web interface with model selection and login functionality.

Deployed on AWS EC2 with Docker, using S3 for cloud-based data storage.

High accuracy and clinical relevance for pathology diagnostics.

🛠️ Tech Stack

Programming Language: Python

Deep Learning Frameworks: PyTorch, TIMM (pretrained model library)

Model Architectures Used: ConvNeXtV2, EfficientViT-B2, SwinV2

Image Preprocessing: Torchvision Transforms (Resize, Normalize, Random Crop, Augmentations)

Optimization & Tuning: Optuna (Bayesian optimization), CosineAnnealingLR, Label Smoothing

Parallelism & Speedup: DataParallel (multi-GPU support), CuDNN enabled

Evaluation Metrics: Accuracy, Confusion Matrix, Model Checkpointing

Data Handling: PyTorch DataLoader, Custom Dataset Class for S3-based image loading

Deployment Framework: Streamlit (for interactive inference UI)

Authentication & UI: Streamlit + HTML/CSS for custom login design

Containerization: Docker (for packaging and deployment)

Cloud Infrastructure:

AWS EC2 – hosting and inference

AWS S3 – storage of image datasets and logs

Version Control: Git + GitHub

Experiment Tracking (Optional): CSV logs, can be extended to MLflow

Miscellaneous: PIL for image reading, NumPy for tensor operations, Matplotlib for visualization

