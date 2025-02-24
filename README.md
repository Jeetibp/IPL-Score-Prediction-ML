IPL Score Prediction with Run Rate Feature
📌 Overview
This project predicts IPL scores using machine learning, incorporating the Run Rate feature for better accuracy. The model is trained on historical IPL data and helps estimate scores based on match conditions.

📊 Features
PowerPlay & Innings-based predictions
Run Rate as a key feature
Linear Regression model for score estimation
Data preprocessing and feature engineering
🛠️ Tech Stack
Python
Pandas & NumPy (Data processing)
Scikit-learn (Model training & evaluation)
Pickle (Model saving & loading)
🚀 Installation
Clone the repository:
bash
Copy
Edit
git clone https:
cd IPL-Score-Prediction-ML
Install dependencies:
bash
Copy
Edit
pip install pandas numpy scikit-learn
📂 Dataset
Ensure you have an IPL dataset with columns like:

Batting Team, Bowling Team, Overs, Total Runs, Wickets, Run Rate, Previous 30 Balls Stats
🏗️ Model Training
To train the model, run:

bash
Copy
Edit
python train_model.py
📈 Usage
To make predictions:

python
Copy
Edit
from model import predict_score
score = predict_score(Bat_team, Bowl_team, overs, total_score, total_wickets, run_rate, prev_runs_30, prev_wickets_30, prev_30_dot_balls, prev_30_boundaries, prev_30_run_rate)
print("Predicted Score:", score)
🎯 Results
Model evaluates score based on multiple match conditions
Mean Absolute Error (MAE) is used for evaluation
Future improvements can include Deep Learning models
📜 License
This project is open-source under the MIT License.
