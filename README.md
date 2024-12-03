# Employee Attrition Classification Project 🎯  

This project explores employee attrition prediction using the **IBM Employee Attrition Dataset** 📊. A total of **650 unique pipelines** combining preprocessing techniques and classification models were tested to identify the most effective approach. 🚀  

## Table of Contents 📑  
- Overview  
- Dataset  
- Key Features  
- Project Workflow  
- Installation  
- Usage  
- Results  
- Contributing  
- License  

## Overview 💡  
The project aims to predict employee attrition by systematically experimenting with combinations of preprocessing techniques and machine learning models. The pipeline design involves:  
- **Sampling Methods**: SMOTE, RandomUnderSampler, None 🔄  
- **Transformations**: LogTransformer, YeoJohnsonTransformer, None 🔧  
- **Scaling Methods**: StandardScaler, MinMaxScaler, RobustScaler, None 📏  
- **Dimensionality Reduction**: PCA, Linear Discriminant Analysis, TruncatedSVD 🎛️  
- **Classifiers**: Logistic Regression, RandomForestClassifier, SVC (Linear, Poly, RBF Kernels) 🔍  

Each pipeline is evaluated based on **Accuracy**, **F1 Score**, **F-beta Score**, and **ROC-AUC**.

## Dataset 📂  
The dataset used for this project is the [IBM Employee Attrition Dataset](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).  

## Key Features 🔑  
1. **Pipeline Design**  
   - Explored 650+ combinations of preprocessing techniques and models. 🔄  
2. **Feature Engineering**  
   - Decomposition, discretization, and feature crossing using domain knowledge 🛠️.  
3. **Anomaly Detection**  
   - Detected anomalies using **Isolation Forest** 🧐.  
4. **Feature Selection**  
   - Used correlation analysis, ANOVA, VIF, chi-squared tests, mutual information, and Random Forest for feature importance 🔍.  
5. **Cluster-Based Modeling**  
   - Applied **KMeans clustering** to identify groups of employees and began assigning models to each cluster for tailored predictions 📊.  

## Project Workflow 🔄  
1. **Data Exploration**  
   - Variable identification, univariate and bivariate analysis 🔎.  
2. **Feature Cleaning**  
   - Addressed missing values, special values, and outliers using Z-Score and IQR 🧹.  
3. **Feature Encoding**  
   - Applied Label Encoding, One-Hot Encoding, Target Encoding, Binary Encoding, and manual mappings 🏷️.  
4. **Model Tuning**  
   - Optimized hyperparameters for the best-performing model (SVC) ⚙️.  
5. **Evaluation**  
   - Metrics include Accuracy, F1 Score, F-beta Score, and ROC-AUC 📊.  

## Installation 🛠️  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/ahmedomer13218/Classification_EmployeeAttrition  
   cd Classification_EmployeeAttrition  
   ```
### Usage 🎮
Open and run the Classification_EmployeeAttrition.ipynb notebook.

### Results 📈
Best Model: SVC with tuned hyperparameters.
Next Steps: Improving results by applying cluster-based modeling to assign different models to clusters identified by KMeans.
### Contributing 🤝
We welcome contributions! If you'd like to contribute, please fork the repository and submit a pull request.

### License 📜
This project is licensed under the MIT License - see the LICENSE file for details.
