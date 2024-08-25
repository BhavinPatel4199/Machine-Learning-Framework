# **Customer Clustering and Credit Risk Classification Using Machine Learning**

## **Project Overview**
This project focuses on clustering customers and classifying loan applicants into "Good" or "Bad" credit risk categories. Using a dataset of 1,000 loan applicants, various machine learning techniques are employed to gain insights that can help financial institutions make better lending decisions.

## **Dataset** : "german_credit_data.csv"

- **Source**: Contains data on 1,000 loan applicants.
- **Features**:
  - Financial information (e.g., income, loan amount)
  - Demographic details (e.g., age, employment status)
  - Credit history and previous loan records
- **Target Variable**: Credit Risk (Good or Bad)

## **Project Structure**
- **`Jupyter_notebook_code_file.ipynb`**: Jupyter Notebook containing the entire workflow, from data preprocessing and clustering to model training and evaluation.
- **`README.md`**: This file provides an overview of the project, setup instructions, and key findings.
- **`german_credit_data.csv`**: The dataset used in this project.

## **Data Preprocessing**
- **Data Cleaning**: Handled missing values, outliers were detected and removed.
- **Feature Engineering**: Created or transformed features to better represent the data.
- **Normalization/Scaling**: Applied feature scaling to ensure all variables contribute equally to the distance measures used in clustering.
- **Data Splitting**: The dataset was split into training and testing sets for model evaluation.

## **Exploratory Data Analysis (EDA)**
- **Visualization**: Used histograms, box plots, and scatter plots to understand feature distributions and relationships.
- **Clustering Tendency**: Conducted a preliminary analysis to assess the natural clustering tendency within the data.

## **Clustering Analysis**
- **Algorithm Used**: K-Means Clustering
  - Grouped similar customers based on financial and demographic information.
  - **Elbow Method**: Determined the optimal number of clusters.
  - **Cluster Interpretation**: Analyzed the characteristics of each cluster and their relation to credit risk.

## **Classification Analysis**
- **Algorithms Used**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- **Model Training**: Trained models to predict whether a loan applicant is a "Good" or "Bad" credit risk.
- **Hyperparameter Tuning**: Employed GridSearchCV to optimize model performance.

## **Model Evaluation**
- **Performance Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- **Best Model**: Highlighted the model that achieved the highest performance metrics and provided a detailed comparison of all models.

## **Conclusion**
- **Summary**: Successfully clustered customers and accurately classified credit risk, offering valuable insights for financial decision-making.
- **Recommendations**: Future work could include advanced clustering techniques or adding more features to improve model performance.


## **Key Learnings**
- Clustering reveals natural groupings in data, aiding in segmentation and targeted marketing.
- Classification models can effectively predict credit risk, enhancing financial decision-making when tuned properly.
