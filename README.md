# Student-Perfomance-Predictor
This project predicts whether a student will pass or fail based on their academic scores and learning habits using a Machine Learning model (Random Forest) trained in a Jupyter Notebook.

Student Performance Predictor - Machine Learning Project

This project predicts whether a student will pass or fail based on their academic scores a
Features Used

Math Score
Science Score
History Score
Attendance Percentage
Weekly Learning Hours
How It Works

The model takes the above inputs from the user.
Preprocessing includes feature scaling using StandardScaler.
A RandomForestClassifier is trained to predict pass/fail (binary classification).
A simple command-line UI or web UI (if added) lets users input values and get results.
Helpful learning resources are recommended if the student is predicted to fail.
How to Run the Project

Option 1: Run in Jupyter Notebook

Clone the repo or download files.
Open student_performance.ipynb in Jupyter Notebook.
Run all cells (this trains, saves the model, and evaluates it).
Option 2: Run Using Python Script in Terminal

Make sure you have Python installed (Python 3.x).
Install required packages:
pip install pandas scikit-learn
