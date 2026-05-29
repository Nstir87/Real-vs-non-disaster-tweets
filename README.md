# Real vs Non-Disaster Tweet Classification

## Overview

Social media platforms often become a primary source of information during emergencies and natural disasters. However, not all disaster-related posts correspond to actual events.

This project develops a Natural Language Processing (NLP) pipeline capable of classifying tweets as either:

- 1 = Real Disaster
- 0 = Not a Real Disaster

The solution demonstrates how machine learning can support emergency response efforts by filtering large volumes of social media content.

## Business Problem

Emergency management organizations face challenges identifying credible information during crisis events.

Automated classification systems can:

- Prioritize relevant reports
- Reduce misinformation
- Improve situational awareness
- Support emergency response decision-making

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn

## Methodology

### Data Loading and Inspection

- Dataset exploration
- Missing value assessment
- Class balance analysis

### Text Preprocessing

- Lowercasing
- Punctuation removal
- Text normalization

### Feature Engineering

- TF-IDF Vectorization

### Modeling

- Logistic Regression

### Evaluation

- Accuracy
- Classification Report
- Prediction Analysis

## Results

The classification model successfully differentiated between genuine disaster-related tweets and unrelated content, demonstrating the effectiveness of TF-IDF feature extraction combined with logistic regression.

## Key Skills Demonstrated

- Natural Language Processing
- Text Classification
- Feature Engineering
- Machine Learning
- Model Evaluation

## Future Improvements

- BERT-based classification
- Transformer architectures
- Real-time tweet ingestion
- Geospatial disaster monitoring

## Author

Nicholas Stirling  
Master of Science in Data Science  
Bellevue University
