## Vallem Keerthi Reddy
👋 Hi! I’m Keerthi Vallem, currently pursuing my Bachelor’s degree in Artificial Intelligence and Data Analytics at IIT Madras.

## 🏅 Olympics Medals Dashboard
- This project focuses on scraping Olympic medal data from Wikipedia, cleaning the data, visualizing medal trends, and building a simple dashboard.
- Source:
https://en.wikipedia.org/wiki/All-time_Olympic_Games_medal_table
## 🔢 MNIST Classification
This project implements and compares multiple machine learning algorithms for handwritten digit classification using the MNIST dataset.
- Dataset: MNIST handwritten digits
- Task: Multi-class classification (digits 0–9)
- Approaches: Traditional ML models, PCA-based dimensionality reduction, and gradient boosting
- Results: KNN and XGBoost with PCA achieved the highest accuracies (≈ 92–93%), with KNN being more time-efficient
## 🔢 Speaker-Independent Spoken Digit Recognition
- A speech recognition project that classifies spoken digits (0–9) using probabilistic sequence models.
- Trained on recordings from 5 speakers and evaluated on an unseen 6th speaker.
- Implemented Gaussian Mixture Models (GMMs) and Hidden Markov Models (HMMs) from scratch.
- Achieved test accuracies of 82.8% (GMM) and 89.6% (HMM), with HMM demonstrating superior speaker-independent recognition performance.
- Source:
https://drive.google.com/file/d/1-b_rnho2Cw9TQRomZ7i21CG_yYHACbBz/view?usp=sharing
## 📁 File Structure
- Olympics_medals_dashboard
  - Olympic_medals_dashboard.ipynb – Complete notebook for data scraping, cleaning, merging, analysis, and visualization
  - nonmedals.csv – Input dataset containing countries that won zero medals
  - medals_merged.csv – Final merged dataset generated after running the notebook
- MNIST-Classification/
  - knn.py – Implementation of the K-Nearest Neighbors (KNN) algorithm
  - Multinomial_Logistic_Regression.ipynb – Multinomial Logistic Regression on MNIST
  - PCA+Logistic.ipynb – PCA followed by Logistic Regression
  - xgboost_.py – MNIST classification using XGBoost
  - xgboost_hyp_pca_.py – XGBoost with PCA and hyperparameter tuning
  - archive - It contains two data sets one is used for training and the other one for validation
- Speaker- Independent-Digit- Recognition
  - results - Contains all the plots required for comparison
            - GMM_Confusion_Matrix.png
            - HMM_Confusion_Matrix.png
            - per_digit_accuracy_comparison.png
  - requirements.txt - All the required libraries
  - src.ipynb - Contains the source code
 

