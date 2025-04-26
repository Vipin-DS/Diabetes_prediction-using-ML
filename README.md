# Diabetes_prediction-using-ML
Dataset We use the PIMA Indians Diabetes Dataset, which contains medical information for several patients, including:  Number of pregnancies  Glucose level  Blood pressure  Skin thickness  Insulin level  BMI (Body Mass Index)  Diabetes Pedigree Function (a function that scores likelihood of diabetes based on family history)  AGE
Each record also has a label:

1 = Diabetic

0 = Not diabetic

Steps Involved
1. Data Collection and Preprocessing
Load the dataset.

Handle missing or zero values (if necessary).

Split the data into features (X) and labels (y).

2. Data Standardization
Since SVM is sensitive to feature scaling, we apply StandardScaler to normalize the feature values to a similar scale.

3. Train-Test Split
We split the data into training set and testing set (e.g., 80% training, 20% testing) using train_test_split.

Stratify the split to maintain the proportion of diabetic/non-diabetic cases.

4. Model Training
We create an SVM classifier (e.g., with kernel='linear') and train it on the training data.

5. Model Evaluation


Why Use Support Vector Machine?
SVMs are powerful for binary classification problems like diabetic vs non-diabetic.

They work well even with smaller datasets.

They try to find the best boundary (hyperplane) that separates the two classes with the maximum margin.

Results
With proper scaling and tuning, SVMs often achieve good accuracy (~75%–80%) on this dataset.

The model can serve as an early screening tool but should not replace professional medical advice.

