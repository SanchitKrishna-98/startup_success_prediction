

# 🚀 Start-up Success Prediction

An interactive machine learning dashboard to predict the success of start-ups and uncover key growth factors that drive investment decisions. Built using Python, Streamlit, and popular ML libraries, this project empowers early-stage investors and entrepreneurs to make data-informed decisions.

## 📊 Overview

This project uses Kaggle’s [Start-up Success Prediction dataset](https://www.kaggle.com/datasets/fmejia21/startup-success-prediction) to train and compare multiple classification models. The best-performing model is deployed using Streamlit to enable real-time predictions and data exploration.

### 🎯 Key Features

- Trained and evaluated multiple models including:
  - K-Nearest Neighbors (KNN)
  - Naive Bayes
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Support Vector Machines (SVM)
- Achieved **87.5% accuracy** with XGBoost
- Visualized feature importance and prediction insights
- Launched a **Streamlit-based web app** to interact with the model
- Analyzed **10,000+ start-up entries** to identify key success indicators

---

## 🧠 Tech Stack

- **Python**
- **Pandas**, **NumPy**
- **scikit-learn**, **XGBoost**
- **Matplotlib**, **Seaborn**
- **Streamlit**

---

## 🛠️ Installation

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/startup-success-predictor.git
   cd startup-success-predictor
   ```

2. Create and activate a virtual environment  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app  
   ```bash
   streamlit run app.py
   ```

---

## 📂 Project Structure

```
startup-success-predictor/
├── data/                   # Dataset files
├── models/                 # Trained models (pickle files)
├── app.py                  # Streamlit frontend
├── model_train.py          # Script to train and evaluate models
├── requirements.txt        # Python dependencies
└── README.md
```

---

## 📈 Results

- XGBoost emerged as the best model with **87.5% prediction accuracy**
- Key features contributing to success: funding total, company age, and number of funding rounds

---

## 🌐 Try It Out

If deployed on Streamlit Cloud or another service, include a link:

🔗 [Live Demo](https://startup-success.streamlit.app)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License

MIT License © 2025 Sanchit Krishna Anandraj

---x
