# Online-Shoppers-Purchasing-Intention

In this project, we aim to predict the purchasing intention of online shoppers using various classification models. The dataset consists of feature vectors belonging to 12,330 sessions, with each session belonging to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

## Data Preparation

We preprocessed the data by encoding, standardizing, and normalizing it. We also handled missing values and noisy data to ensure that the dataset was suitable for analysis.

## Exploratory Data Analysis

We performed exploratory data analysis to gain insights into the relationships between the features and revenue. We used seaborn and matplotlib to visualize the data and identify patterns and trends.

## Feature Engineering

We applied feature engineering techniques to enhance the predictive power of the models. This included creating new features and transforming existing ones to better capture the relationships between the features and revenue.

## Model Training

We split the data into training, testing, and validation sets. We then trained various classification models, including Logistic Regression, Perceptron Linear Classifier (PLA), Multi-Layer Perceptron (MLP), K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Naïve Bayes, on the training set.

## Model Evaluation

We evaluated the performance of the models using accuracy, precision, recall, and F1 score. We found that the Random Forest model had the highest accuracy, with a score of 0.9239.

## Model Performance Analysis

We analyzed the performance of the Random Forest model to determine if it overfitted the data. We found that the model did not overfit and had a stable performance on the testing set.

## Clustering

We performed clustering on the dataset by ignoring the class label. We used K-Means Clustering to identify patterns and groups in the data. We measured the performance of the clustering models using silhouette score and found that K-Means with k=2 had the highest score. However, on application of the Elbow Method to find the optimal # of clusters, we found it to be 6. Data distributions with both these cluster numbers have been plotted, and it has been observed that there is comparatively less overlap when k=6.

## Conclusion

In this project, we predicted the purchasing intention of online shoppers using various classification models. We found that the Random Forest model had the highest accuracy and did not overfit the data. We also performed clustering on the dataset and found that K-Means with k=5 had the highest silhouette score. Overall, this project demonstrates the power of machine learning techniques in predicting and understanding customer behavior in online shopping.
