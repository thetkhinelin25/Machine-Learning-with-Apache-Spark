# Machine Learning with Apache Spark Capstone Project

Project Title: NASA Airfoil's Sound Level Prediction based on NASA Airfoil Self Noise dataset 

  

Description: The project aims to predict the sound level of airfoils using the NASA Airfoil Self Noise dataset. By leveraging machine learning techniques, the goal is to develop a predictive model that accurately estimates the noise levels generated by airfoils based on various aerodynamic features. This project involves data preprocessing, model training, evaluation, and model persistence. 

  

Methodology: The methodology involved several key steps. Initially, an ETL (Extract, Transform, Load) process was carried out, where the CSV dataset was loaded, duplicates were removed, null values were dropped, and necessary data transformations were applied. The cleaned data was then stored in Parquet format. Following data preparation, a machine learning pipeline was created using Linear Regression to predict airfoil sound levels. The model was trained and evaluated using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²). Finally, the trained model was persisted by saving it for future use. 

  

Results: The data cleaning process resulted in a high-quality dataset stored in Parquet format. The Linear Regression model was successfully trained, demonstrating its capability to predict airfoil sound levels. The evaluation metrics showed the model's performance with specific values for MSE, MAE, and R², indicating the model's accuracy. The trained model was saved, ensuring it can be utilized for future predictions without the need for retraining, thus achieving the project's goals of developing an effective predictive tool for airfoil sound levels. 
