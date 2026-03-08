# FairLens_Hackathon

# Responsible AI Dashboard
A Fairness-Aware Machine Learning Evaluation Tool

## Overview
Responsible AI Dashboard is a Streamlit-based web application that helps evaluate machine learning models for fairness, bias, and transparency.

The application allows users to upload datasets, train a machine learning model, analyze predictions, and detect potential bias across different demographic groups. The goal is to promote ethical and responsible AI development.

## Features

### Model Training
- Upload a CSV dataset
- Select the target column
- Automatically trains a classification model
- Generates predictions

### Bias & Fairness Detection
- Detects bias across demographic groups
- Calculates fairness-related statistics
- Highlights groups with prediction disparities

### Model Risk Score
- Generates a simple risk score based on:
  - Model accuracy
  - Prediction imbalance
- Helps quickly assess model reliability

### What-If Simulator
- Modify feature values manually
- Observe how predictions change
- Understand model decision behavior

### Performance Summary
Displays key model metrics:
- Accuracy
- Precision
- Recall

### Clean Dashboard Interface
- Built with Streamlit
- Simple and intuitive layout
- Interactive data exploration

## Tech Stack
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Plotly

## Project Structure
```
Responsible-AI-Dashboard
│
├── app.py                # Main Streamlit application
├── model.py              # Machine learning training logic
├── fairness.py           # Bias and fairness calculations
├── utils.py              # Helper functions
├── requirements.txt      # Project dependencies
└── README.md
```

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/responsible-ai-dashboard.git
cd responsible-ai-dashboard
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
streamlit run app.py
```

## How to Use
1. Start the Streamlit application
2. Upload a CSV dataset
3. Select the target column
4. Train the machine learning model
5. Explore:
   - Model performance
   - Bias detection
   - Risk score
   - What-if simulation

## Purpose

This project promotes:
- Ethical AI development
- Bias detection in machine learning
- Transparent model evaluation
- Responsible deployment of AI systems

## Future Improvements

- Multiple model comparison
- Advanced fairness metrics
- Explainable AI integration (SHAP / LIME)
- Automated bias mitigation techniques
- Exportable fairness reports

## License
This project is open-source and available under the MIT License.
