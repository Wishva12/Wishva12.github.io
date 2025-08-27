---
title: "📱 Reddit Sentiment Analysis Pipeline"
date: 2024-05-20
categories: [machine-learning, nlp, data-science]
tags: [python, scikit-learn, xgboost, mlflow, nlp, sentiment-analysis]
header:
  teaser: /assets/images/projects/reddit-sentiment/thumbnail.jpg
  overlay_image: /assets/images/projects/reddit-sentiment/model-comparison.png
  overlay_filter: 0.5
  caption: "ML pipeline with XGBoost and MLflow tracking"
---

## 🎯 Project Overview

<span class="status-badge status-completed">Completed</span>

![Model Performance Comparison](/assets/images/projects/reddit-sentiment/model-comparison.png)
*Performance comparison of different ML models for sentiment classification*

Developed a comprehensive sentiment analysis pipeline for Reddit comments, featuring advanced preprocessing, model stacking, and experiment tracking for robust sentiment classification.

## 🧠 Model Performance Results

![Confusion Matrix](/assets/images/projects/reddit-sentiment/confusion-matrix.png)
*Detailed classification results showing model accuracy across sentiment categories*

## 📊 MLflow Experiment Tracking

![MLflow Dashboard](/assets/images/projects/reddit-sentiment/mlflow-tracking.png)
*Comprehensive experiment tracking and model management with MLflow*

## ✨ Key Features

- 🔍 **Advanced Preprocessing** - Text cleaning, tokenization, and feature engineering
- 🎯 **Model Stacking** - Ensemble of XGBoost, LightGBM, and traditional ML models
- ⚖️ **Class Balancing** - Handling imbalanced datasets with SMOTE and other techniques
- 🔧 **Hyperparameter Tuning** - Optuna for automated optimization
- 📈 **Experiment Tracking** - MLflow for reproducible ML workflows
- 📊 **Performance Analysis** - Detailed metrics and visualization

## 🛠️ Technologies Used

<span class="skill-tag ai">XGBoost</span>
<span class="skill-tag ai">LightGBM</span>
<span class="skill-tag">Scikit-learn</span>
<span class="skill-tag">MLflow</span>
<span class="skill-tag">Optuna</span>
<span class="skill-tag">NLTK</span>
<span class="skill-tag">Python</span>

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|---------|----------|
| XGBoost | 87.3% | 86.1% | 87.8% | 86.9% |
| LightGBM | 85.9% | 84.7% | 86.2% | 85.4% |
| Ensemble | **89.1%** | **88.4%** | **89.7%** | **89.0%** |

## 🔄 ML Pipeline

1. **Data Collection** - Reddit API integration and data extraction
2. **Preprocessing** - Text cleaning, normalization, and feature extraction
3. **Model Training** - Multiple algorithms with cross-validation
4. **Hyperparameter Tuning** - Automated optimization with Optuna
5. **Model Evaluation** - Comprehensive performance analysis
6. **Deployment Ready** - Serialized models for production use

## 🎯 Key Insights

- **Ensemble methods** significantly outperform individual models
- **Text preprocessing** is crucial for social media sentiment analysis
- **Class balancing** improves minority class detection by 15%
- **Feature engineering** with n-grams and TF-IDF boosts performance

---

<a href="#" class="cta-button">🚀 Try Demo</a>
<a href="https://github.com/Wishva12/reddit-sentiment" class="cta-button secondary">📋 View Code</a>