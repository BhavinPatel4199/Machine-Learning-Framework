# **Iris Flower Classification using Machine Learning Algorithms**

## **Project Overview**
This project focuses on classifying iris flowers into three species—Setosa, Versicolor, and Virginica—based on sepal and petal measurements. The classification is achieved using various machine learning algorithms, including Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, Random Forest, and Support Vector Machine (SVM). The project involves data exploration, preprocessing, model training, hyperparameter tuning, and evaluation.

## **Dataset** : "iris.xlsx"
- **Source**: The dataset used is the famous Iris dataset, a staple in machine learning.
- **Features**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- **Target Variable**: Iris Species (Setosa, Versicolor, Virginica)

## **Project Structure**
- **`jupyter_notebook_code_file.ipynb`**: Jupyter Notebook containing all code from data loading to model evaluation.
- **`coed_pdf_file.pdf`**: PDF report summarizing the entire project with visualizations and detailed analysis.
- **`README.md`**: This markdown file provides an overview of the project, setup instructions, and key findings.
- **`iris.xlsx`**: The dataset used in this project.

## **Data Preprocessing**
- **Data Cleaning**: The dataset is clean with no missing values.
- **Feature Engineering**: No additional features are engineered; existing features are used directly.
- **Data Splitting**: The dataset is split into training and testing sets using an 80-20 split.

## **Exploratory Data Analysis (EDA)**
- **Visualization**: Pair plots, histograms, and box plots are used to explore relationships between features.
- **Insights**:
  - Petal length and width are significant indicators for differentiating between the species.
  - Setosa is easily separable, while Versicolor and Virginica have overlapping features.

## **Model Implementation**
- **Algorithms Used**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
- **Hyperparameter Tuning**: GridSearchCV is employed to find optimal hyperparameters for each model.

## **Model Evaluation**
- **Performance Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - Confusion Matrix
- **Best Model**: The Random Forest classifier achieved the highest accuracy with strong precision and recall values for all three classes.

## **Conclusion**
- **Summary**: The project successfully classifies iris flowers with high accuracy using machine learning models. The Random Forest model is the most effective, though all models performed reasonably well.
- **Future Work**: Further improvements could include testing more advanced models, feature importance analysis, and expanding the dataset with additional features or synthetic data.


## **Key Learnings**
- EDA is crucial for understanding the data before model application.
- Hyperparameter tuning can significantly enhance model performance.
- Random Forest is robust for classification tasks with overlapping features.


