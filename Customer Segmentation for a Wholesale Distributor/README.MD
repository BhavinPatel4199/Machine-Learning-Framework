# Customer Segmentation for a Wholesale Distributor

## Overview
This project aims to describe the variation in different types of customers that a wholesale distributor interacts with, based on their annual spending across various product categories. The project involves data cleaning, exploratory data analysis (EDA), feature selection, clustering, and classification using machine learning techniques.

## Dataset
The dataset contains the annual spending in monetary units on diverse product categories by clients of a wholesale distributor. The key features include:

- **Region**: The region where the customer is located.
- **Channel**: The type of channel (e.g., retail, Horeca).
- **Fresh**: Annual spending on fresh products.
- **Milk**: Annual spending on milk products.
- **Grocery**: Annual spending on grocery items.
- **Frozen**: Annual spending on frozen products.
- **Detergents_Paper**: Annual spending on detergents and paper products.
- **Delicassen**: Annual spending on delicatessen products.

## Project Workflow
1. **Data Exploration & Cleaning**:
   - Explored the dataset to understand the distribution and relationships between features.
   - Cleaned the data by handling missing values and outliers.

2. **Feature Scaling**:
   - Implemented MinMaxScaler and StandardScaler to normalize the data.
   - Selected the scaler that provided the most normalized distribution of features.

3. **Feature Selection**:
   - Used Recursive Feature Elimination with Cross-Validation (RFECV) to identify the optimal number of features.

4. **Clustering**:
   - Applied KMeans clustering for different values of `K` and used the elbow method to find the optimal number of clusters.

5. **Dimensionality Reduction**:
   - Performed Principal Component Analysis (PCA) to reduce the dimensionality of the data.
   - Analyzed the variance explained by the first two and four components.

6. **Classification**:
   - Implemented an XGBoost classifier with 5-fold cross-validation.
   - Reported performance metrics such as accuracy, precision, recall, and F1 score.

## Results
- **Optimal Features**: Identified through RFECV.
- **Optimal Clusters**: Determined using the elbow method in KMeans.
- **PCA Analysis**: Explained variance by the first two and four components and visualized clusters.
- **XGBoost Classifier**: Achieved high accuracy and robust performance on classification tasks.

## Installation
To run this project, you will need to have the following installed :

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

## Conclusion
- The project successfully identified distinct customer segments based on their spending patterns across various product categories. 
- By leveraging KMeans clustering and PCA for dimensionality reduction, meaningful insights were gained into how customers can be grouped, which can inform targeted marketing strategies. 
- The XGBoost classifier demonstrated strong predictive performance in classifying customer segments, further validating the effectiveness of the feature selection and clustering process.

## Key Learnings
- Data Preparation: Proper data cleaning and scaling are crucial steps in ensuring that machine learning models perform effectively, especially in clustering and classification tasks.
- Feature Selection: Utilizing RFECV for feature selection can significantly improve model performance by identifying the most relevant features and reducing noise.
- Clustering Techniques: KMeans clustering, combined with the elbow method, is an effective approach for identifying natural groupings in data, especially when paired with dimensionality reduction techniques like PCA.
- Dimensionality Reduction: PCA not only reduces the complexity of the data but also aids in better visualization and interpretation of clusters.
- Model Performance: The XGBoost classifier proved to be a robust model for classification tasks, demonstrating the importance of hyperparameter tuning and cross-validation in achieving optimal results.
