# Podcast-Listening-Time-Prediction-Kaggle
Kaggle Playground Series S5E4: Predicting Podcast Listening Time
# 🎧 Podcast Listening Time Prediction

This repository contains my solution for the [Kaggle Playground Series S5E4](https://www.kaggle.com/competitions/playground-series-s5e4/overview) competition.  
The task was to **predict the listening time (in minutes) of podcast episodes** based on metadata like genre, popularity, ads, and sentiment.

---

## 📌 Competition Goal
- Target variable: **Listening_Time_minutes**
- Predict podcast listening time using metadata:
  - Episode length
  - Host & guest popularity
  - Genre, publication day & time
  - Sentiment of the episode
  - Number of ads

---

## 📂 Repository Contents
- `Predict_Podcast_Listening_Time.ipynb` → Jupyter Notebook with:
  - Data preprocessing
  - Feature engineering
  - Model training (Random Forest Regressor)
  - RMSE evaluation
- `submission2.csv` → Final submission file with predictions (highest-scoring run on Kaggle Public Leaderboard)
- `README.md` → Project description and results

---

## 🏆 Results
- Achieved **final submission** after the deadline with `submission2.csv`
- Model: **RandomForestRegressor** with tuned hyperparameters
- Best RMSE achieved on validation set (local): ~ _(fill in your local RMSE here)_
- Kaggle Public Leaderboard Score: **_(fill in your score here)_**

---

## 📸 Leaderboard Screenshot
To verify results, here’s my leaderboard snapshot from Kaggle:

![Leaderboard Screenshot](images/leaderboard.png)



---

## 🚀 Tech Stack
- **Python**
- **Pandas, NumPy** for data wrangling
- **Scikit-learn** for ML models & evaluation
- **Matplotlib/Seaborn** for visualization
- **Jupyter Notebook** for experimentation

---

## 📖 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Podcast-Listening-Time-Prediction-Kaggle.git
   cd Podcast-Listening-Time-Prediction-Kaggle
2. Open the notebook:
   ```bash
   jupyter notebook Predict_Podcast_Listening_Time.ipynb
3.Run the cells to retrain the model or generate predictions.

