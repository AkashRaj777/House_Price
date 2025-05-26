# House Price Prediction System

This project aims to predict house prices accurately using machine learning techniques, focusing on delivering a practical solution for buyers, sellers, and real estate analysts. It combines data preprocessing, model training, and a simple web interface for real-time price estimation.

The first step involves data preprocessing and cleaning, where the raw housing dataset undergoes handling of missing values, encoding categorical features, outlier treatment, and feature scaling. Temporal features like year built and sold are also transformed to capture market trends. The cleaned and processed data is saved into a structured CSV file, ready for model training.

In the second step, the preprocessed dataset is used to train and evaluate multiple regression models, including Linear Regression, Decision Tree, and Random Forest. Models are compared using metrics like R², MAE, and RMSE to identify the best performer. The Random Forest Regressor emerges as the most accurate and reliable model, which is then saved for future predictions.

Finally, a simple web application is built using HTML, CSS, and JavaScript, consisting of two pages: a home page where users input property details such as location, size, number of bedrooms, bathrooms, and year built, and a results page that displays the predicted house price. The backend leverages the saved Random Forest model to generate predictions dynamically, providing users with an easy-to-use interface for estimating property values.

This end-to-end system combines data science and web development to create a user-friendly tool for house price prediction, with potential for further enhancements like adding more features or improving the UI.

