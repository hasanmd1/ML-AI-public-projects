<h1 align="center">Resume visible projects for show case only</h1>

<p align="center">
  <img src="assets/ML&&AI.png" alt="Project Overview" width="350">
</p>

<!-- --- -->

## Table of Contents

- [Why This Repo?](#why-this-repo)
- [Learning Path](#learning-path)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Why This Repo?

This repository is designed for **resume visible projects for show case only**. Each project is a standalone Jupyter notebook that you can clone and run immediately.

You can learn or verify:
- **Data Cleaning and Preprocessing** - preparing real-world messy data
- **Exploratory Data Analysis** - visualizations and statistical insights
- **Machine Learning** - classification, regression, and anomaly detection
- **Deep Learning** - CNNs, transfer learning, and NLP models
- **Computer Vision** - detection, recognition, and pose estimation

## Learning Path

Start from the top and work your way down. Projects are ordered by difficulty within each level.

### Level 1 - Fundamentals

Starting with pandas, sklearn, and basic ML workflows.

| # | Project | Focused On | Category |
|---|---------|-------------------|----------|
| 1 | [Titanic Survival Prediction](Titanic%20Survival%20Prediction) | EDA, data cleaning, feature engineering, 7 classifiers, GridSearchCV | Classification |
| 2 | [Iris Flower Classification](Iris%20Flower%20Classification) | Image classification with CNNs, data loading | Classification |
| 3 | [Customer Churn](Customer%20Churn) | Logistic regression from scratch, prediction on new data | Classification |
| 4 | [Heart Failure Prediction](Heart%20Failure%20Prediction) | Feature analysis, multiple classifiers, model evaluation | Classification |
| 5 | [Rental Prices of AirBnb](Rental%20Prices%20of%20AirBnb) | Linear regression, outlier analysis, label encoding | Regression |

### Level 2 - Text and NLP

Work with text data, preprocessing pipelines, and NLP techniques.

| # | Project | Focused On | Category |
|---|---------|-------------------|----------|
| 6 | [Message Spam Filtering](Message%20Spam%20Filtering) | TF-IDF, text preprocessing, SVM classification | NLP |
| 7 | [Cyber-Bullying Prediction](Cyber-Bullying%20Prediction) | NLP pipeline, GridSearchCV, model comparison | NLP |
| 8 | [Sentiment Analysis](Sentiment%20Analysis) | Logistic regression from scratch, Twitter data, NLTK | NLP |
| 9 | [AirBnb Reviews Sentimental Analysis](AirBnb%20reviews%20Sentimental%20Analysis) | Full NLP pipeline: preprocessing, ML, deep learning, LLMs | NLP |

### Level 3 - Computer Vision and Deep Learning

Work with images, neural networks, and pre-trained models.

| # | Project | Focused On | Category |
|---|---------|-------------------|----------|
| 10 | [Gender Classification](Gender%20Classification) | EfficientNetV2, transfer learning, Keras | Classification |
| 11 | [Face Detection](Face%20Detection) | Haar cascades, MTCNN, OpenCV | Computer Vision |
| 12 | [Face Recognition](Face%20Recognition) | LBPH algorithm, real-time webcam recognition | Computer Vision |
| 13 | [Eye Disease Detection](Eye%20Disease%20Detection) | ResNet34, data augmentation pipeline, medical imaging | Computer Vision |
| 14 | [Alzheimer Detection](Alzheimer%20Detection) | Clinical data analysis, Random Forest on medical data | Computer Vision |

### Level 4 - Advanced Topics

Handle more complex real-world alike problems.

| # | Project | Focused On | Category |
|---|---------|-------------------|----------|
| 15 | [Network Intrusion Detection System](Network%20Intrusion%20Detection%20System) | Ensemble methods, XGBoost, KDD Cup dataset | Anomaly Detection |
| 16 | [Object Detection](Object%20Detection) | YOLOv8, Faster R-CNN, RetinaNet, Detectron2 | Computer Vision |
| 17 | [Pose Estimation](Pose%20Estimation) | YOLOv8, MediaPipe, activity classification | Computer Vision |
| 18 | [Robotics and Computer Integrated Manufacturing](Robotics%20and%20Computer%20Integrated%20Manufacturing) | MobileNetV2, transfer learning, industrial imaging | Robotics |

## Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook or JupyterLab

### Core Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Additional Libraries - via project

| Project Type | Install |
|-------------|---------|
| Deep Learning | `pip install tensorflow keras` |
| Computer Vision | `pip install opencv-python` |
| NLP | `pip install nltk` |
| Object Detection | `pip install ultralytics` |

Each project has its own `requirements.txt` for exact dependencies:

```bash
cd "Project Folder Name"

pip install -r requirements.txt

jupyter notebook
```

### Quick Start

```bash
git clone https://github.com/hasanmd1/Machine-Learning---AI---public-projects.git ML_AI_proj

cd ML_AI_proj

# Pick a project and run it
cd "Selected Proj.."

pip install -r requirements.txt

jupyter notebook
```

## Contributing

Contributions are not allowed!! Please read our [Contributing Guide](CONTRIBUTING.md) before any contribution.

## License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="MIT License"></a>
</p>
