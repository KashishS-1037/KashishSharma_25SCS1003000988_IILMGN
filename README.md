# 🏏 Cricket Score & Win Prediction Engine

A Machine Learning-based system designed to predict **match win probabilities** and **final score outcomes** in T20 cricket using a combination of statistical models and heuristic logic.

---

## 📌 Project Description

This project tackles the challenge of predicting outcomes in fast-paced T20 cricket matches. It combines:

* A **Machine Learning model** for win probability prediction
* A **rule-based engine** for realistic score estimation

The system is designed to simulate real-time match analysis and provide meaningful insights for fans, analysts, and developers.

---

## 🚀 Key Features

* 🔢 **Win Prediction Model**

  * Built using Logistic Regression
  * Outputs probability instead of just win/loss

* 📊 **Score Prediction Engine**

  * Uses match conditions like overs & wickets
  * Adapts based on match phases

* 📈 **Visualization Support**

  * Displays trends and model insights

* 🔌 **API Integration**

  * Easily usable in other applications

---

## 🧠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## ⚙️ Working

### 1. Win Predictor

* Uses historical match data
* Applies One-Hot Encoding on categorical features
* Predicts probability using Logistic Regression

### 2. Score Predictor

* Uses a rule-based approach:

  * Powerplay (0–6 overs)
  * Middle overs (7–15)
  * Death overs (16–20)
* Considers:

  * Current run rate
  * Wickets lost
  * Match phase

---

## 📂 Project Structure

```
data/              # Dataset files
models/            # Trained models
src/               # Source code
main.py            # Main execution file
README.md
```

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/your-username/cricket-predictor.git
cd cricket-predictor
pip install -r requirements.txt
python main.py
```

---

## 📊 Results

* ~55% accuracy in win prediction
* More realistic score prediction than basic run-rate methods

---

## 🔮 Future Scope

* Live match API integration
* Advanced ML models (XGBoost, LSTM)
* Web dashboard for visualization

---

## 👨‍💻 Contributors

* Pratap Khandelwal
* Tanu Goyal
* Kashish Sharma
* Aarush Chauhan

---

## ⭐ Support

If you found this project useful, consider giving it a **star ⭐ on GitHub!**
