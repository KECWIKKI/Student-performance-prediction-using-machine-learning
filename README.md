# Student Performance Prediction Using Machine Learning

## Overview
This project focuses on developing a machine learning model to predict the academic performance of students based on various factors. The aim is to build a robust and efficient prediction system using various machine learning techniques. The project is implemented and can be executed in Google Colab.

## Features
- Predicts the academic performance of students.
- Utilizes machine learning algorithms for high accuracy.
- Easy to use and integrate into other projects.
- Supports analysis of performance across 12 different programs from a private university.

## Getting Started

### Prerequisites
- Google account to use Google Colab
- Basic knowledge of Python and machine learning concepts

### Open the Colab Notebook
1. Go to [Google Colab](https://colab.research.google.com/).
2. Open the notebook using the following link: [Student Performance Prediction Notebook](https://colab.research.google.com/github/your-username/student-performance-prediction-using-machine-learning/blob/main/AML_MINI_PROJECT.ipynb)

### Dataset
- The dataset used in this project is titled: `Dataset on the academic performance of students in 12 programmes from a private university.xlsx`
- Ensure the dataset is uploaded in the Colab environment or accessible from your local machine.

## Usage

### Running the Notebook
1. Open the notebook in Google Colab.
2. Upload the dataset `Dataset on the academic performance of students in 12 programmes from a private university.xlsx` to your Colab environment.
3. Follow the step-by-step instructions provided in the notebook.
4. Run the cells sequentially to:
   - Load and preprocess the data.
   - Train the machine learning model.
   - Evaluate the model.
   - Predict the academic performance of new student data.

### Example
```python
# Load data and preprocess
data = preprocess_data("Dataset on the academic performance of students in 12 programmes from a private university.xlsx")

# Train model
model = train_model(data)

# Predict performance
student_data = {'feature1': value1, 'feature2': value2, ...}
performance = predict_performance(model, student_data)
print(performance)
# Output: 'High', 'Medium', or 'Low' performance
