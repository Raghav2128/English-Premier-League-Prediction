# ⚽ English Premier League Match Outcome Predictor

Predict the outcome of football matches using machine learning — trained on real historical match data.

---

## 🧠 Project Overview

This project explores how machine learning can be applied to football analytics by predicting match outcomes: Home Win, Draw, or Away Win. It includes two key parts:

1. **Data Collection:** Scrape Premier League data (fixtures, results, shooting stats) from FBref using Python and BeautifulSoup.
2. **Prediction:** Use the scraped and cleaned dataset to train a logistic regression model and evaluate its accuracy.

The goal of this project was both educational and practical: to gain experience in data preprocessing, feature encoding, and model evaluation using real-world sports data.

---

## 🚀 Features

- Scrape match data from [fbref.com](https://fbref.com/)
- Clean and analyze historical football match data
- Encode categorical labels (Home, Away, Draw)
- Train a Logistic Regression model to predict outcomes
- Evaluate model performance using accuracy and confusion matrix
- Simple, modular, and reproducible notebooks

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** – for data manipulation and preprocessing
- **scikit-learn** – for model building, encoding, and evaluation
- **BeautifulSoup** – for scraping football data from FBref
- **Requests** – to make HTTP calls to web pages
- **Jupyter Notebook** – for interactive development and experimentation

---

## 📁 Getting Started

### 1. Clone the repository
```sh
git clone https://github.com/Raghav2128/English-Premier-League-Prediction.git
```
### 2. Install Dependencies
```sh
pip install -r requirements.txt
```
### 3. Run the notebook
```sh
jupyter notebook predictions.ipynb
```
---

## ✅ Future Improvements

- Add more match features (e.g. team ranking, recent form, player stats)
- Experiment with more advanced models (Random Forests, XGBoost)
- Tune hyperparameters for better accuracy
- Build a simple web interface to allow user input and live predictions

---

## 📬 Contact

Have questions or feedback? Feel free to reach out or open an issue on GitHub.

