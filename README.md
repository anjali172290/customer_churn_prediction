##### Customer Churn Prediction Using Machine Learning
### Overview
Customer churn is a critical challenge for businesses, as retaining customers is often more cost-effective than acquiring new ones. 
This project aims to predict customer churn using machine learning techniques by analyzing historical data, identifying key patterns, and building a predictive system.
### Features of the Project
1. Data Understanding and Preparation:
Customer ID column removed as it is irrelevant for modeling.
Missing values in the TotalCharges column were replaced with 0.
Class imbalance in the target variable addressed using SMOTE (Synthetic Minority Oversampling Technique).
Exploratory Data Analysis (EDA):

2.Analysis of numerical features using distributions, box plots, and correlation heatmaps.
Examination of categorical features using count plots.
Data Preprocessing:

3.Label encoding for categorical features and the target variable.
Splitting the dataset into training and testing subsets.
Model Training:

4.Various machine learning models were trained with default hyperparameters.
Random Forest outperformed other models in terms of accuracy.
Model Evaluation:

5.Performance metrics and visualizations were used to assess model effectiveness.
Deployment:

6.A predictive system was developed to load the trained model and make real-time predictions.

### Libraries Used
Pandas: For data manipulation and analysis.
NumPy: For numerical computations.
Matplotlib & Seaborn: For data visualization.
Scikit-learn: For machine learning modeling and evaluation.
Imbalanced-learn: For addressing class imbalance using SMOTE.

### Installation
1.Open the Colab Notebook
  Open the Google Colab link provided or upload the notebook directly to your Google Drive.
2. Install Required Dependencies
  Run the following command in a Colab cell to install required libraries:
  !pip install -r requirements.txt
3. Run the Notebook
  Execute each cell in the notebook sequentially to perform data analysis, train the model, and use the predictive system.

### Results
Key Findings
The Random Forest model outperformed others, achieving the best accuracy.
A predictive system was developed to identify customers likely to churn.

### Future Scope
# Potential Improvements
Hyperparameter tuning to improve model performance.
Integrating the predictive system into a web or mobile application for real-time use.
Exploring advanced techniques like deep learning for further improvements.

### Technologies Used
# Programming Language
Python
# Libraries
pandas, numpy for data manipulation.
matplotlib, seaborn for visualization.
scikit-learn for machine learning models.
imbalanced-learn for handling class imbalance.

### Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

### Contact
For any inquiries or suggestions, feel free to reach out at:

Email: anjali22057779@gmail.com
