Crop Recommendation System using Machine Learning

This project aims to build an intelligent crop recommendation system using machine learning models based on various environmental parameters. It helps farmers or agricultural stakeholders make data driven decisions about the most suitable crop to cultivate under given conditions.

The dataset used is `crop_recommdation.csv` and contains the following features:
1. Temperature (°C)
2. Humidity (%)
3. Ph (pH of the soil)
4. Water availability (mm)
5. season (rainy, summer, spring, etc.)
6. label (recommended crop)

Machine Learning Models Used - 
The notebook evaluates and compares the following ML models:
1. Logistic Regression
2. Linear Regression (exploratory purposes)
3. Support Vector Classifier (SVC)
4. Random Forest Classifier
5. KMeans Clustering

Key Steps in the Pipeline - 
1. Data Preprocessing
   - Handling categorical variables (`season`)
   - Splitting data into training and test sets

2. Model Training
   - Training multiple models using `sklearn`
   - Evaluating using accuracy and MSE

3. Crop Prediction
   - Based on user input (via UI or script)
   - Predicts the best crop for given conditions

Performance Metrics - 
1. Accuracy Score: Used for classification models
2. Mean Squared Error: Used for regression-based models

Tech Stack - 
1. Python
2. Pandas
3. Numpy
4. Scikit-learn

License - 
This project is licensed under the MIT License.
