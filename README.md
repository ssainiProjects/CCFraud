# Credit Card Fraud Detection: A Comparative Analysis of Traditional Machine Learning and Neural Network Approaches

This project explores and compares traditional machine learning models (XGBoost, Random Forest) with neural network architectures (MLPs) for detecting fraud in two imbalanced datasets: the Kaggle European Credit Card Fraud dataset and the PaySim mobile money transaction dataset.

### Key Research Questions
1. How do traditional machine learning models compare with neural networks in detecting credit card and mobile money fraud?
2. What techniques can be used to manage class imbalance across both datasets?
3. How do traditional models and neural networks compare in terms of complexity and computational efficiency?

The project is implemented using Python, with key tools including:

- **scikit-learn** for machine learning models
- **TensorFlow/Keras** for neural networks
- **pandas**, **numpy**, **matplotlib**, and **seaborn** for data manipulation and visualization

This project is now complete. The final report details how traditional ML models, particularly XGBoost, outperformed the MLP in this study, delivering better detection performance and computational efficiency. 
It also explains how SMOTE demonstrated its usefulness by addressing the data imbalance without compromising the majority class, and RandomUnderSampler led to unusable results. 

All code can be found in 2 files:
'Kaggle CCFraud Code Submission.html' AND  
'paysim fraud code submission.html'

Datasets:

Kaggle Europen Fraud Dataset: 
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

Paysim Fraud Dataset:
https://www.kaggle.com/datasets/ealaxi/paysim1
