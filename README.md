# 🫀 Heart Disease Prediction System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-red.svg)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--learn-green.svg)
![OCR](https://img.shields.io/badge/OCR-Tesseract-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)


A machine learning–powered web app that predicts the likelihood of heart disease using clinical data such as age, blood pressure, and cholesterol levels. Built with Python, scikit-learn, and Streamlit, this project demonstrates how AI can support early health-risk prediction.

---

## ⚙️ Features
- Multiple ML models: Logistic Regression, Random Forest, and XGBoost
- Automatic data preprocessing: cleaning, encoding, scaling
- Performance metrics visualization: Accuracy, Precision, Recall, F1-score
- Real-time web interface using Streamlit
- Model saving for future predictions

---

## 🧩 Project Structure
Heart-Disease-Prediction/
- Data/ → dataset folder  
- Models/ → saved model artifacts  
- Utils/ → helper functions  
- app.py → Streamlit interface  
- data_preparation.py → data processing  
- model_training.py → training and evaluation  
- requirements.txt → dependencies  
- README.md → documentation

---

## 🧠 Dataset Information
- Source: UCI Cleveland Heart Disease dataset  
- Samples: 303  
- Features: 13 clinical attributes  
- Goal: Predict heart disease presence (binary classification)

⚠️ Disclaimer: This project is for educational and research purposes only and is not a medical diagnostic tool.

---

## 🛠️ Tech Stack
- Python 3.8+  
- scikit-learn  
- XGBoost  
- Pandas, NumPy  
- Matplotlib, Plotly  
- Streamlit

---

## 🚀 Getting Started
1️⃣ Clone the repository  
`git clone https://github.com/HassanRasheed91/Heart-Disease-Prediction.git`  
`cd Heart-Disease-Prediction`

2️⃣ Create a virtual environment  
- Windows:  
  `python -m venv venv`  
  `venv\Scripts\activate`  
- macOS/Linux:  
  `python -m venv venv`  
  `source venv/bin/activate`

3️⃣ Install dependencies  
`pip install -r requirements.txt`

4️⃣ Train the model  
`python model_training.py`

5️⃣ Run the Streamlit app  
`streamlit run app.py`  
Then open your browser at 👉 http://localhost:8501

---

## 📊 Input Features
- age — Age of the patient  
- sex — Gender (1 = male, 0 = female)  
- cp — Chest pain type  
- trestbps — Resting blood pressure  
- chol — Serum cholesterol (mg/dl)  
- fbs — Fasting blood sugar > 120 mg/dl  
- restecg — Resting ECG results  
- thalach — Maximum heart rate achieved  
- exang — Exercise-induced angina  
- oldpeak — ST depression induced by exercise  
- slope — Slope of the peak exercise ST segment  
- ca — Number of major vessels (0–3)  
- thal — Thalassemia type

---

## 🧪 Model Evaluation
- Uses train/test split with cross-validation  
- Evaluates Accuracy, Precision, Recall, and F1-score  
- Best performing model is integrated into Streamlit app

---

## 🤝 Contributing
1. Fork the repository  
2. Create a branch: `git checkout -b feature-name`  
3. Commit changes: `git commit -m "Added feature"`  
4. Push: `git push origin feature-name`  
5. Open a Pull Request 🚀

---

## 📜 License
Licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 👨‍💻 Maintainer
Hassan Rasheed | 📧 221980038@gift.edu.pk | 🌐 https://github.com/HassanRasheed91

---

⭐ If you like this project, please give it a star on GitHub — it motivates me to build more awesome open-source ML projects 🚀
!**

*Made with ❤️ by [Hassan Rasheed](https://github.com/HassanRasheed91)*

</div>
