# Breast-Cancer-Diagnosis-An-Exploratory-Data-Analysis

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) on a breast cancer diagnosis dataset. The dataset contains various medical features extracted from digitized images of fine needle aspirates (FNAs) of breast masses, categorized into mean, standard error, and worst values. The goal is to analyze key patterns, relationships, and feature importance in distinguishing malignant and benign cases.

Through data cleaning, statistical analysis, and visualization techniques like histograms, box plots, and correlation heatmaps, this study identifies critical predictors of breast cancer. Insights from this analysis can be used for further predictive modeling and clinical decision-making. 🚀

Dataset link:- https://www.kaggle.com/datasets/chrismorgan86/breast-cancer-wisconsin-original

1. **Import Libraries** – Loads essential Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn for data analysis and visualization.  
2. **Load and Glimpse of Dataset** – Reads the dataset and provides an initial overview using functions like `.head()`, `.info()`, and `.describe()`.  
3. **Data Preprocessing** – Handles missing values, duplicate removal, feature scaling, and encoding categorical variables for better model performance.  
4. **EDA (Exploratory Data Analysis)** – Uncovers key patterns using summary statistics, visualizations, and feature distributions.  
5. **Correlation Analysis** – Identifies relationships between variables using correlation matrices and heatmaps to find the most relevant features.  
6. **Boxplot** – Visualizes feature distributions and detects outliers in the dataset.  
7. **Histogram** – Shows frequency distributions of numerical features to understand data spread.  
8. **Split Features and Target** – Separates independent variables (features) from the dependent variable (target) for model training.  
9. **KNN Model** – Implements the K-Nearest Neighbors algorithm to classify malignant and benign cases.  
10. **Random Forest** – Trains a Random Forest classifier to improve predictive accuracy and interpret feature importance.  
11. **XGBoost** – Applies the XGBoost algorithm for high-performance classification.  
12. **Cross Validation for XGBoost** – Evaluates XGBoost model performance using cross-validation techniques.  
13. **Gradient Boosting** – Implements Gradient Boosting to compare its performance with other models.  
14. **Comparing the Results and Picking the Best Model** – Analyzes model performance using metrics like accuracy, precision, recall, and F1-score to determine the best classifier.  
 😊
