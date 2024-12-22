# 🧠 Stroke Prediction using Machine Learning in R  

[![R](https://img.shields.io/badge/Made%20with-R-blue?style=flat&logo=R&logoColor=white)](https://cran.r-project.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=flat)](https://opensource.org/licenses/MIT)  
[![Build Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat&logo=check)](#)  
![GitHub repo size](https://img.shields.io/github/repo-size/<your-username>/<repo-name>?style=flat&logo=github)  
![GitHub last commit](https://img.shields.io/github/last-commit/<your-username>/<repo-name>?style=flat)  

## 🖍️ Overview  

This project leverages **machine learning algorithms**—Random Forest, Naive Bayes, and Support Vector Machine (SVM)—to predict the likelihood of a stroke based on patient health data. The analysis was conducted entirely in R and documented in R Markdown (Rmd).  

### Key Highlights:  
- **📊 Dataset**: Sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset) containing 11 features and over 5,000 records.  
- **🎯 Goal**: Develop a reliable AI-powered tool for stroke risk prediction.  
- **🚀 Performance**: The optimized Random Forest model achieved 97.7% accuracy on imbalanced test data, with an AUC of 99.93% after oversampling and tuning.  

## 🔍 Detailed Analysis  

### 📂 Dataset and Preprocessing  
The dataset contains demographic and medical attributes such as age, BMI, glucose levels, and smoking status. Key steps in preprocessing included:  
1. Handling missing values using imputation methods.  
2. Addressing class imbalance using SMOTE (Synthetic Minority Oversampling Technique).  
3. Feature engineering, normalization, and one-hot encoding.  

### 🛠️ Methodology  
1. **Exploratory Data Analysis (EDA)**: Insights into class distribution, correlations, and outliers.  
2. **Model Implementation**: Baseline models were trained and evaluated. Techniques such as hyperparameter tuning and oversampling were applied to improve performance.  
3. **Evaluation Metrics**: Accuracy, F1 score, sensitivity, and AUC were used to assess model performance.  

### 📈 Results  

| Model            | Accuracy | F1 Score | AUC   |  
|-------------------|----------|----------|-------|  
|  Random Forest  | 97.7%    | 99.9%    | 99.93%|  
|  Naive Bayes    | 94.3%    | 94.8%    | 99.93%|  
|  SVM (Tuned)    | 84.0%    | 85.1%    | 90.8% |  

**💡 Conclusion**: The Random Forest model with oversampling emerged as the best performer, demonstrating the highest accuracy and robustness against class imbalance.  

## 🚀 Future Work  
- 📥 Incorporating additional features such as cholesterol and physical activity data.  
- 📚 Exploring advanced techniques like XGBoost and deep learning models.  
- 💻 Enhancing computational efficiency using feature selection methods.  

## ▶️ How to Run  
1. Clone this repository.  
2. Install the required R libraries using:  
   ```R  
   install.packages(c("caTools", "ROSE", "smotefamily", "randomForest", "e1071", "fastDummies"))  
   ```  
3. Run the R Markdown file (`analysis.Rmd`) to reproduce the results.  

## 📜 License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
