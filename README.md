## End to End ML Project

# 📊 ML Flask Prediction App

This is an end-to-end machine learning application built using **Flask** for serving predictions via a web UI and **Scikit-learn, XGBoost, CatBoost** for model training and prediction.

It takes user input from a web form, processes the data using a custom pipeline, and returns the predicted result — all wrapped in a clean UI.

---

## 🚀 Features

- Web-based input form using **Flask + HTML**
- Custom ML pipeline for prediction
- Modular code structure with `src/` directory
- Logging of predictions and errors
- Extensible with any ML model
- Package management using `setup.py`

---

## 🧠 Tech Stack

- Python 3.10+
- Flask
- Pandas, NumPy
- Scikit-learn
- XGBoost, CatBoost
- HTML/CSS (Jinja templates)
- Logging with timestamps

---

## 💡 How It Works

1. User visits the web form via the browser
2. Inputs values such as gender, education, scores, etc.
3. Data is wrapped in a `CustomData` class and passed to a `PredictPipeline`
4. Model prediction is returned and shown on the page

---
## 📦 Installation & Run Locally

### 1. Clone the repository
git clone https://github.com/Diksha20Kam/ml-flask-predictor.git
cd ml-flask-predictor

### 2. Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate

### 3. Install all dependencies
pip install -r requirements.txt

### 4. Run the Flask app
python app.py