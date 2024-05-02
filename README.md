# Auomated_ML_algorithm_recommender_for_predictive_analytics

This repository hosts the Automated ML Algorithm Recommender System, designed to streamline the process of selecting the optimal machine learning algorithms for various predictive analytics tasks. By analyzing dataset characteristics, this system provides robust, scalable, and tailored recommendations, enhancing the efficiency and efficacy of predictive analytics workflows across multiple domains such as finance, healthcare, and more.

## Project Description

The system leverages algorithm performance profiling, meta-learning, and advanced feature engineering analysis to recommend the most suitable machine learning algorithms. It aims to address common challenges such as limited dataset coverage, algorithm bias, and the need for scalability and interpretability in automated recommendations. Our system supports a variety of data inputs and integrates seamlessly with existing workflows, offering a customizable and user-friendly interface for all users.

## System Overview

The system is structured to handle multiple stages of the machine learning workflow, from data ingestion and preprocessing to model evaluation and selection. It supports a variety of data formats and implements robust preprocessing to enhance data quality, followed by intelligent task identification and model recommendation.

### Data Ingestion and Standardization

- **Support for Multiple Formats**: Accepts input data in CSV, Excel, and JSON formats.
- **Data Standardization**: Converts all incoming data into a uniform CSV format to ensure consistency and ease of processing.

### Data Preprocessing

- **Comprehensive Techniques**: Implements Missing Values Imputation, Data Normalization, and Categorical Data Encoding to maintain data integrity.
- **Automated Transformation**: Utilizes a Column Transformer to apply the necessary transformations seamlessly.

### Task Identification

- **Intelligent Classification**: Automatically determines whether a dataset should be treated as a classification or regression task based on the properties of the target variable.
- **Task-Specific Handling**: Identifies binary/categorical targets for classification tasks and continuous targets for regression tasks.

### Model Recommendation

- **Versatile Algorithm Portfolio**: Offers a selection of algorithms for both classification and regression tasks, including RandomForest, LogisticRegression, and SVC.
- **Adaptability**: Chooses algorithms to cover a spectrum of complexities and learning types, catering to diverse data characteristics.

### Model Evaluation and Selection

- **Data Splitting**: Divides the dataset into training (80%) and test (20%) subsets to validate model performance.
- **Performance Metrics**: Evaluates models using the accuracy score for classification tasks and R2 score for regression tasks.
- **Optimal Model Selection**: Picks the model with the highest performance score for deployment or further hyperparameter tuning.

## Tech Stack

1. ### Programming Language
- Python: This is the primary programming language used, favored for its extensive libraries and frameworks that facilitate machine learning and data processing.
2. ### Machine Learning Libraries
- Scikit-learn: Used for implementing machine learning algorithms like RandomForest, LogisticRegression, and SVC. It's also used for preprocessing, model evaluation, and selecting the best model.
- Pandas: Essential for data manipulation and analysis, particularly useful in the data ingestion and standardization process.
NumPy: Integral for handling numerical operations which are ubiquitous in machine learning tasks.

## Features

- **Multi-format Data Input**:Accepts data in formats like CSV, Excel, JSON, and more, automatically standardizing it for processing.
- **Preprocessing**:  Implements missing value imputation, data normalization, and categorical encoding to prepare data for analysis.
- **Dynamic Algorithm Recommendation**: Utilizes a range of algorithms including RandomForest, LogisticRegression, SVM, KNeighbors, DecisionTree, and GaussianNB, tailored to the specific analytical needs of the dataset.
- **High Customizability**: Offers options for customization and integration, allowing the system to adapt to various user requirements and existing infrastructures.
- **Enhanced User Experience**: Provides a user-friendly interface that simplifies the complex process of algorithm selection.

## Limitations

- Limited dataset coverage which may not represent all real-world scenarios.
- Potential algorithm bias and challenges in generalization across diverse datasets.
- Needs enhancements in scalability, interpretability, and user customization.

## Prerequisites

- Python 3.8 or higher
- pip

## Contributors
- Omisha Singal
- Santhana Lakshmi
- Sai Hemanth Kilaru



