### SOund NAvigation AND Ranging (SONAR)

**Sonar Detection Model**

**Overview**

This project aims to develop a machine learning model to distinguish between mines and rocks based on sonar data. 
The dataset consists of response metrics for 60 different sonar frequencies ranging from 0.0 to 1.0, sent to known objects such as mines (metal cylinders) and rocks. 
The challenge involves classifying these objects using various machine learning algorithms and tuning their hyperparameters to achieve the best performance.

**Dataset**

Features: 60 sonar frequency metrics (ranging from 0.0 to 1.0)
Labels:
"M" for mines
"R" for rocks

**Algorithms and Hyperparameter Tuning: **

Different machine learning algorithms were tested, including:

   1. Logistic Regression
   2. Decision Tree
   3. Random Forest
   4. Support Vector Machine (SVM)
   5. Naive Bayes
   6. K-Nearest Neighbors (KNN)

Hyperparameters were tuned using techniques like RandomizedSearchCV to find the optimal configuration for each algorithm.

**Results :**

After extensive experimentation and tuning, the Random Forest (RF) algorithm performed the best. 
The model achieved high accuracy and demonstrated strong performance in distinguishing between mines and rocks.

**Performance Metrics:**

1. Logistic Regression: Accuracy: 0.74
2. Decision Tree: Accuracy: 0.67
3. Random Forest: Accuracy: 0.95
4. SVM: Accuracy: 0.90
5. Naive Bayes: Accuracy: 0.69
6. KNN: Accuracy: 0.86

**Conclusion**

The Random Forest model emerged as the best performer in classifying sonar data into mines and rocks. 
The project highlights the importance of selecting the right algorithm and tuning hyperparameters for optimal performance in machine learning tasks.
