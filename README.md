# spotify-genre-classification
This repository delves into the exploration and classification of music genres using Spotify song data. It implements a comprehensive data analysis workflow, encompassing preprocessing techniques and the evaluation of various machine learning models for multi-class classification.

#### Data:
- The dataset employed for this project consists of Spotify song features, which will be specified in detail within the notebook. It is based on the `top10s.csv` dataset from Kaggle, focusing on Spotify’s top songs from 2010 to 2019.
- <a href="https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year">Kaggle link.</a>

#### Data Analysis and Preprocessing: 
A thorough examination of the data is conducted, including:
- Exploratory Data Analysis (EDA) to understand the distribution of features and identify potential relationships.
- Data visualization techniques (histograms, boxplots, scatter plots) to gain insights into the data.
- Missing value imputation and handling strategies.
- Feature scaling.
- Feature Engineering: It includes feature transformation and data cleaning to prepare the dataset for machine learning models.

#### Model Training:
- The notebook implements and evaluates the performance of the following machine learning models for multi-class genre classification (Logistic Regression, Random Forest, KNN, SVM, XGBoost, Gradient Boosting, LightGBM, AdaBoost and Decision Tree).
- Hyperparameter tuning strategies (GridSearchCV, RandomizedSearchCV).
- Evaluation metrics, such as accuracy, precision, recall, F1-score, and confusion matrix, are employed to assess the effectiveness of each model.
