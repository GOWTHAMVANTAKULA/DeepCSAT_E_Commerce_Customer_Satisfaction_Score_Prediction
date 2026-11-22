# DeepCSAT_E_Commerce_Customer_Satisfaction_Score_Prediction
Built an E-Commerce Customer Satisfaction (CSAT) prediction system using machine learning and Artificial Neural Networks (ANN) to analyze customer support data, predict satisfaction scores, identify key factors, and classify customers into high and low satisfaction groups.

# E-Commerce Customer Satisfaction (CSAT) Prediction
This project focuses on predicting customer satisfaction (CSAT) scores using Machine Learning and Artificial Neural Networks (ANN). It analyzes e-commerce customer support data to understand factors influencing customer satisfaction and classify customer experiences into High and Low satisfaction categories.

The goal is to use historical customer interaction data to support data-driven decisions, improve customer service quality, and identify areas that require attention.

## 🎯 Project Objectives

- Predict customer satisfaction scores using Artificial Neural Networks.
- Classify customer interactions into High and Low satisfaction categories.
- Analyze customer support factors influencing satisfaction.
- Perform data preprocessing and feature engineering.
- Evaluate model performance using appropriate metrics.
- Develop a prediction interface for user interaction.

## 📊 Dataset Information

The dataset contains approximately 85,907 customer support records.

Important features include:

| Feature | Description |
|---|---|
| channel_name | Customer interaction channel |
| category | Main issue category |
| Sub-category | Specific issue type |
| Product_category | Product category |
| Item_price | Product price |
| Agent_name | Customer support agent |
| Supervisor | Assigned supervisor |
| Manager | Assigned manager |
| Tenure Bucket | Agent experience category |
| Agent Shift | Agent working shift |
| Handling_Time_min | Customer handling time |
| CSAT Score | Customer satisfaction score (Target) |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Artificial Neural Networks (ANN)
- Google Colab
- Gradio

## ⚙️ Project Workflow

### 1. Data Collection and Understanding
- Loaded the customer support dataset.
- Explored dataset dimensions, columns, and data types.
- Analyzed the distribution of customer satisfaction scores.

### 2. Data Preprocessing
- Handled missing values.
- Selected relevant features.
- Encoded categorical variables.
- Scaled numerical features.
- Split the dataset into training and testing sets.

### 3. Exploratory Data Analysis (EDA)
- Analyzed CSAT score distribution.
- Examined customer support characteristics.
- Identified class imbalance in the target variable.

### 4. Model Development

Two prediction approaches were explored:

**ANN Regression**
- Predicts numerical CSAT scores.
- Uses Dense layers with ReLU activation.
- Applies Dropout to reduce overfitting.
- Uses Adam optimizer and Mean Squared Error (MSE) loss.

**ANN Binary Classification**
- Converts CSAT scores into High and Low satisfaction categories.
- Uses a Sigmoid-based classification output.
- Evaluates the model using classification metrics.

### 5. Model Evaluation

**Regression Metrics**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

**Classification Metrics**
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

Special attention is given to class imbalance because accuracy alone may not represent the model's ability to identify low-satisfaction customers.

### 6. Model Deployment / User Interface

A Gradio-based interface was developed to allow users to enter customer support details and obtain satisfaction predictions from the trained classification model.

## 🧠 Key Learning Outcomes

- Understanding and preprocessing real-world customer support data.
- Handling imbalanced classification datasets.
- Implementing Artificial Neural Networks using TensorFlow/Keras.
- Understanding regression versus classification.
- Applying feature encoding and scaling.
- Evaluating models using multiple performance metrics.
- Building an interactive prediction interface using Gradio.

## 🚀 Future Improvements

- Improve minority-class prediction performance.
- Experiment with different classification algorithms.
- Perform hyperparameter tuning.
- Improve model generalization.
- Explore explainable AI techniques to understand important customer satisfaction factors.
- Improve the deployment interface.

