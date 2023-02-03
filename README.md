# Breast-Cancer-Detection
Breast cancer detection using machine learning models.


## 1. Dataset
We used the UCI Machine Learning Repository. <br>
Link: http://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+%28diagnostic%29 <br>
The dataset was created by Dr. William H. Wolberg, physician at the University Of Wisconsin Hospital at Madison, Wisconsin, USA. <br>

## 2. Programming Language, Libraries and IDE
**Programming Language**: Python 3 <br>
**Libraries**: pandas, numpy, seaborn, and sklearn <br>
**IDE**: Jupyter Notebook <br>

## 3. Basic Mathematics
### 3.1 Mean
Mean is the average of the given numbers and is calculated by dividing the sum of the given numbers by the total number of numbers. <br>
Mean of a random varibale X, **μ = Σ(X<sub>i</sub>)/n** <br>
### 3.2 Standard Deviation
Standard deviation is a measure of how dispersed the data is in relation to the mean. <br>
Standard deviation of a population X, **σ = (Σ(X<sub>i</sub> - μ)<sup>2</sup>/n)<sup>1/2</sup>**
### 3.3 Correlation
Correlation describes the strength of association between two variables. <br>
Pearson correlation coefficient between two random variables X and Y can be calculated by the formula: <br>
![Img 1](https://wikimedia.org/api/rest_v1/media/math/render/svg/9d8faa0a3dd65575e246c185a14ece2096c2186d)
### 3.4 Standarization
Standardization scales each input variable separately by subtracting the mean and dividing by the standard deviation to shift the distribution to have a mean of zero and a standard deviation of one. <br>
Formula for standarization: **x<sub>new</sub> = (x<sub>old</sub>-μ)/σ**

## 4. Machine Learning Models
1. Logistic Regression Classifier
2. Nearest Neighbor Classifier
3. Support Vector Machines Classifier
4. Kernel SVM Classifier
5. Naive Bayes Classifier
6. Decision Tree Classifier
7. Random Forest Classifier

## 5. Metrics
1. F1 Score
2. Accuracy Score <br>

**Confusion Matrix:** <br>
![Screenshot (14)](https://user-images.githubusercontent.com/58243776/216496572-5dad9ba5-9bf2-4192-91f6-33cd64d19f62.png)


**Precision** = TP/(TP + FP) <br>
**Recall** = TP/(TP + FP) <br>
**F1 Score** = 2*(Precision * Recall)/(Precision + Recall) <br>
**Accuracy Score** = (TP + TN)/(TP + FP + FN + TN)

## 6. Result
**Accuracy Score:**
1. Logistic Regression — 97.36% <br>
2. Nearest Neighbor — 94.73% <br>
3. Support Vector Machines — 95.61% <br>
4. Kernel SVM — 98.24% <br>
5. Naive Bayes — 96.49% <br>
6. Decision Tree Algorithm — 95.61% <br>
7. Random Forest Classification — 97.36% <br>

**F1 Score:**
1. Logistic Regression — 96.47% <br>
2. Nearest Neighbor — 93.02% <br>
3. Support Vector Machines — 94.25% <br>
4. Kernel SVM — 97.61% <br>
5. Naive Bayes — 95.23% <br>
6. Decision Tree Algorithm — 93.97% <br> 
7. Random Forest Classification — 96.38% <br>
