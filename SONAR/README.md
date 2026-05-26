# Sonar Rock vs Mine Prediction using Deep Learning

A Deep Learning project that classifies sonar signals as either **Rock (R)** or **Mine (M)** using an Artificial Neural Network (ANN) built with TensorFlow and Keras.

This project demonstrates the complete machine learning workflow including:
- Data preprocessing
- Model building
- Training and evaluation
- Prediction
- Performance analysis
- Dropout regularization

---

## Project Overview

Sonar signals are used to detect objects underwater.  
This model predicts whether the detected object is:
- **Rock**
- **Mine**

The dataset contains numerical sonar signal readings collected from bouncing sound waves.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- TensorFlow / Keras
- Scikit-learn

---

## Machine Learning Workflow

### 1. Data Loading
- Imported the Sonar dataset using Pandas

### 2. Data Preprocessing
- Checked for missing values
- Split features and labels
- Encoded categorical target values

### 3. Train-Test Split
- Dataset split into training and testing sets

### 4. ANN Model Building
Built a Deep Learning model using:
- Dense Layers
- ReLU Activation
- Sigmoid Output Layer

### 5. Model Training
- Trained the model on sonar signal data
- Evaluated model performance using accuracy metrics

### 6. Prediction & Evaluation
- Generated predictions on test data
- Used:
  - Classification Report
  - Confusion Matrix

### 7. Dropout Regularization
- Implemented Dropout layers to reduce overfitting
- Compared performance with and without Dropout

---

## Model Architecture

### Basic ANN Model
- Input Layer: 60 neurons
- Hidden Layers:
  - 60 neurons
  - 30 neurons
  - 15 neurons
- Output Layer:
  - 1 neuron (Binary Classification)

### ANN with Dropout
- Added Dropout layers for regularization
- Improved generalization performance

---

## Dataset

Dataset: Sonar Dataset  
Target Classes:
- R → Rock
- M → Mine

Features:
- 60 numerical sonar frequency attributes

---

## Results

The model successfully classifies underwater objects using sonar signals with good prediction accuracy.

Evaluation metrics used:
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Project Structure

```bash
├── SONAR.ipynb
├── sonar_dataset.csv
└── README.md
```

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
```

### 2. Navigate to Project Folder

```bash
cd YOUR_REPOSITORY
```

### 3. Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn tensorflow
```

### 4. Run the Notebook

Open Jupyter Notebook and run:

```bash
SONAR.ipynb
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deployment using Streamlit
- Visualization dashboard
- Model optimization

---
