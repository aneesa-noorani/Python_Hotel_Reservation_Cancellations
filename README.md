# Hotel_Reservation_Cancellations
Project Objective: Classify which hotel reservations will end up being cancelled

Project Outline:
1) Data Preprocessing - handle outliers, drop leaked columns, handle numerical & categorical missing values, collapse categorical columns, combine columns
2) Exploratory Visualization
3) Evaluation Metric Decision - chose recall as metric of choice, since we want to minimize false negatives
4) Machine Learning Algorithms, Part I - KNN, Logistic Regression, Linear SVM, SVM with kernels, Decision Trees

Decision trees gave best recall score, at 57.67%. In the next part of the project, I apply more advanced algorithms to obtain a higher recall score.

5) Machine Learning Algorithms, Part II:
  a. Hard & Soft Voting Classifiers
  b. Bagging, Pasting, Adaboosting
  c. Gradient Boosting
  d. PCA
  e. Deep Learning

This time, Gradient Boosting gave the best recall score, at 70.61%
