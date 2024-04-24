# Spotify-Popularity-Predictor
The Spotify Popularity Predictor is a machine learning-based model that predicts the degree of popularity and classifies songs as 'Popular' or 'Not Popular.' The model leverages Linear Regression to estimate the actual degree of popularity, achieving an accuracy of 75%. Additionally, the Decision Tree Classifier and Logistic Regression models classify songs into categories of popularity with an accuracy of 100%. The model uses various features from the Spotify dataset and advanced data preprocessing techniques to achieve these results, making it a powerful tool for analyzing song popularity.
**Data Preprocessing**: The model processes the Spotify dataset, removing unnecessary columns and encoding categorical features.
**Feature Scaling**: Numerical features are scaled using MinMaxScaler to normalize the data for better model performance.
**Linear Regression**: This algorithm predicts the actual popularity degree of a song based on input features, achieving 75% accuracy.
**Decision Tree Classifier**: Classifies songs as 'Popular' or 'Not Popular' based on the entropy criterion, achieving 100% accuracy.
**Logistic Regression**: Classifies songs as either '-1', '0', or '1' based on their popularity index, using logistic regression for classification.
**Model Training and Testing**: Models are trained on a subset of the data and tested on another subset to evaluate their performance.
**Model Persistence**: The trained Decision Tree Classifier is saved for later use in predicting song popularity.
