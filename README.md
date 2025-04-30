# Multi-Factor-Forest-Fire-Prediction-Model
# Predictive Forest Fire Risk Assessment Model

## Overview
This project develops a predictive forest fire risk assessment model using machine learning techniques to analyze multiple factors, including weather conditions, vegetation data, and human activities. The objective is to accurately predict fire risk levels (High, Medium, Low) to assist forest management teams with real-time risk prediction, enabling early intervention and efficient resource allocation.

## Data Sources
- **Meteorological APIs**: For weather conditions.
- **Remote Sensing Satellites**: For vegetation data.
- **Historical Fire Records**: For past fire incidents.

## Data Preprocessing
- Handled missing values.
- Normalized and encoded features.
- Conducted feature engineering to identify key predictors, with **Temperature** and **Drought Moisture Code (DMC)** being the most influential.

## Model Development
- **Train-Test Split**: 80-20 split.
- **Evaluation Metrics**: R², Mean Squared Error (MSE), and accuracy.
- **Model Selection**: 
  - Linear Regression achieved 95.15% accuracy but lacked robustness.
  - Random Forest was selected for deployment with 90.38% accuracy due to better generalization on multi-dimensional data.

## Challenges
- **Data Inconsistency**: Addressed by implementing data cleaning and imputation techniques to ensure high-quality datasets for training.

## Deployment
- Deployed as a REST API using Flask.
- Integrated real-time risk level outputs (High, Medium, Low) for better decision-making.
- Features interactive visualizations using Matplotlib and Plotly for easy assessment of fire risk.

## Results
This project successfully created a real-time prediction API, enabling forest departments to act early in high-risk zones. The scalable model architecture allows adaptation to different geographic regions and seamless integration with existing forest management tools, improving data-driven decision-making in disaster prevention and resource allocation.

## Usage
Refer to the documentation for setup instructions and API usage details.

