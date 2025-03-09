Implementation of Personal Fitness Tracker using Python

Overview

This project is a Personal Fitness Tracker built using Streamlit and Machine Learning. The app predicts the number of calories burned based on user input and visualizes fitness-related insights.

Features

User Input Panel: Users can input Age, BMI, Exercise Duration, Heart Rate, Body Temperature, and Gender.

Calorie Prediction: Uses a Random Forest Regressor model to estimate calories burned.

Data Visualization: Displays histograms, scatter plots, and correlation heatmaps to analyze fitness trends.

Model Evaluation: Shows RMSE and R-squared scores for model accuracy.

Feature Importance Analysis: Highlights key factors influencing calorie burn.

Downloadable Results: Users can download predictions as CSV files.

Feedback System: Users can provide feedback on predictions.

Interactive Prediction: Real-time prediction updates based on slider adjustments.

Dataset

The model is trained on two datasets:

calories.csv – Contains calorie consumption data.

exercise.csv – Includes user demographic and exercise data.

Tech Stack

Frontend: Streamlit

Backend: Python (Pandas, Scikit-Learn, Seaborn, Matplotlib)

Machine Learning Model: Random Forest Regressor

Installation & Setup

Prerequisites

Python 3.x

Streamlit

Pandas

Scikit-Learn

Matplotlib

Seaborn

Steps to Run the Project

Clone the repository:

git clone <repository-url>

Navigate to the project folder:

cd personal_fitness_tracker

Install dependencies:

pip install -r requirements.txt

Run the Streamlit app:

streamlit run app.py

Model Details

Algorithm Used: Random Forest Regressor

Hyperparameters:

n_estimators=1000

max_features=3

max_depth=6

Train-Test Split: 80%-20%

Future Improvements

Implement a Neural Network model for better accuracy.

Add more fitness metrics like steps count, sleep data, and hydration level.

Deploy the app using Streamlit Cloud or Heroku.

Enhance UI with custom CSS for a better user experience.

License

This project is open-source and available under the MIT License.

Contact

For any queries or contributions, reach out via:

Email: jyeshas708@gmail.com

LinkedIn: www.linkedin.com/in/yeshasj
