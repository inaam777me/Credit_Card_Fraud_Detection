# 💳 Credit Card Fraud Detection Using Deep Learning

A Deep Learning project that detects fraudulent credit card transactions using TensorFlow/Keras. This project applies data preprocessing, feature engineering, model training, and evaluation techniques to classify transactions as legitimate or fraudulent.

---

## 📌 Project Overview

Credit card fraud is a major challenge in the financial industry. This project builds a binary classification model that predicts whether a credit card transaction is fraudulent based on transaction features.

The model is trained on a dataset containing over **300,000 real-world credit card transactions** with anonymized features.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions
- Build an Artificial Neural Network (ANN) using TensorFlow/Keras
- Reduce false positives while maintaining high detection accuracy
- Visualize training and validation performance

---

## 📊 Dataset Information

The dataset contains approximately **300,000+ transactions** with the following features:

| Feature | Description |
|---------|-------------|
| Time | Seconds elapsed between each transaction |
| V1 - V28 | PCA-transformed confidential transaction features |
| Amount | Transaction amount |
| Class | Target variable (0 = Legitimate, 1 = Fraudulent) |

### Target Classes

- **0** → Legitimate Transaction
- **1** → Fraudulent Transaction

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📚 Python Libraries

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score

from tensorflow import keras
from tensorflow.keras.models import Sequential
from tensorflow.keras.layers import Dense
```

---

## 🧠 Model Architecture

The neural network consists of:

- Input Layer (30 Features)
- Dense Layer (256 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Dense Layer (1024 Neurons, ReLU)
- Output Layer (1 Neuron, Sigmoid)

---

## ⚙️ Model Configuration

| Parameter | Value |
|-----------|-------|
| Optimizer | Adam |
| Loss Function | Binary Crossentropy |
| Activation | ReLU & Sigmoid |
| Batch Size | 4096 |
| Epochs | 100 |
| Validation Split | 20% |

---

## 🚀 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore and clean the data
4. Split data into training and testing sets
5. Build the Deep Neural Network
6. Train the model
7. Evaluate model performance
8. Visualize training and validation results

---

## 📈 Performance Evaluation

The model is evaluated using:

- Binary Accuracy
- Training Loss
- Validation Loss

Training history is visualized using Matplotlib to monitor learning performance.

---

## 📂 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
├── README.md
├── requirements.txt
├── dataset/
│   └── creditcard.csv
├── images/
│   ├── loss.png
│   ├── accuracy.png
│   └── model_summary.png
└── LICENSE
```

---

## ▶️ Getting Started

### Clone the repository

```bash
git clone https://github.com/yourusername/Credit-Card-Fraud-Detection.git
```

### Navigate to the project folder

```bash
cd Credit-Card-Fraud-Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

Open:

```
Credit_Card_Fraud_Detection.ipynb
```

using Jupyter Notebook or Google Colab.

---

## 📦 Requirements

```
tensorflow
keras
numpy
pandas
matplotlib
scikit-learn
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 💡 Future Improvements

- Hyperparameter tuning
- Class imbalance handling using SMOTE
- Cross-validation
- Model checkpointing
- Precision-Recall and ROC Curve analysis
- Compare ANN with Random Forest and XGBoost
- Deploy the model using Flask or FastAPI

---

## 📖 Learning Outcomes

Through this project, I gained practical experience in:

- Data preprocessing
- Machine Learning
- Deep Learning
- Binary Classification
- TensorFlow & Keras
- Neural Networks
- Data Visualization
- Model Evaluation
- Fraud Detection
- Python Programming

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Inaam**

- GitHub: https://github.com/yourusername
- LinkedIn: https://www.linkedin.com/in/your-linkedin-profile/

If you found this project helpful, consider giving it a ⭐ on GitHub.
