# GENAI_ML_CAPSTONE
### This is my capstone project for my genai_ml course by E&amp;ICT academy, IIT Kanpur

## Autonomous Driving – Vehicle Detection & Classification

This project focuses on building a deep learning-based computer vision system to detect and classify vehicles from images. The model performs both object classification and bounding box prediction, simulating real-world autonomous driving use cases.

### Key Features
Multi-class vehicle classification (cars, trucks, buses, etc.)

Bounding box prediction for object localization

Comparison of multiple deep learning architectures

Visualization of predictions on test images

Tech Stack

Python, OpenCV, NumPy, Pandas

TensorFlow / Keras

Pretrained Models: ResNet50, MobileNet, VGG16, EfficientNetB0

### Results

Achieved ~66% classification accuracy using EfficientNetB0

Improved localization performance with optimized bounding box regression

Conducted comparative analysis across models to select the best performer

-------------------------------------------------------------------------------------------------------------------------------------------------------------
# Sales Forecasting
### Overview

This project implements a machine learning-based sales forecasting system using historical sales data. The goal is to predict future sales trends and provide actionable insights for business decision-making.

Sales forecasting is a critical component of business analytics, enabling better inventory planning, demand estimation, and revenue optimization.

This notebook demonstrates a complete end-to-end data science workflow, from raw data to predictive modeling.

### Problem Statement

Accurately predict future sales using historical data by:

Identifying patterns and seasonality

Engineering meaningful features

Training regression models

Evaluating prediction performance

### Dataset

The dataset used in this project includes:

📅 Date (time-based feature)

🏪 Store / Product identifiers

📦 Sales / Quantity sold

👉 The dataset is treated as a time-series forecasting problem.

### Exploratory Data Analysis (EDA)

Key steps performed:

Data cleaning and missing value handling

Time-series visualization of sales trends

Seasonality and trend detection

Correlation analysis

### Insights:
Sales exhibit temporal patterns (daily/monthly trends)

Seasonal spikes indicate periodic demand changes

Certain features strongly influence sales

### Feature Engineering

To improve model performance, the following features are created:

📆 Date-based features:

Year, Month, Day, Weekday

⏳ Lag features (previous sales values)

📊 Rolling statistics (moving averages)

🔢 Encoding categorical variables

These transformations help models learn temporal dependencies and seasonality.

### Machine Learning Models

Linear Regression

Decision Tree Regressor

Random Forest Regressor

(Optional) XGBoost

Tree-based models are particularly effective as they capture non-linear relationships and feature interactions.

### Model Evaluation

Models are evaluated using standard regression metrics:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

##### The best model is selected based on accuracy and generalization performance.

### Results
Successfully built a predictive model for sales forecasting

Captured trend and seasonality patterns

Identified key drivers influencing sales

Achieved reliable prediction accuracy

### 💡 Business Insights
📦 Helps optimize inventory levels

📊 Improves demand planning

📢 Enables targeted marketing strategies

💰 Supports revenue forecasting

## Tech Stack
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

### How to Run
###### Clone repository
git clone https://github.com/Ashutosh-Mi/GENAI_ML_CAPSTONE.git

###### Navigate
cd GENAI_ML_CAPSTONE

###### Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

###### Run notebook
jupyter notebook


