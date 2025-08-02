# 📊 Customer Churn Predictor — Streamlit + Machine Learning App

**Customer Churn Predictor** is a machine learning web application built with **Streamlit** that predicts whether a telecom customer is likely to churn or not. It uses a classification model trained on the **Telco Customer Churn dataset** and offers a user-friendly interface for real-time predictions.

---

## 🚀 Features

- 📈 **Churn Prediction** – Predicts churn probability based on customer inputs  
- 🧠 **Trained ML Model** – Uses Random Forest Classifier  
- 🖥️ **Streamlit UI** – Clean and interactive web interface  
- 📦 **Modular Codebase** – Separation of concerns for model, preprocessing, and UI  
- 📂 **Data Integration** – Based on the public `Telco-Customer-Churn.csv` dataset  

---

## 🛠️ Tech Stack

| Component     | Tech Used                   |
|---------------|-----------------------------|
| Frontend UI   | Streamlit                   |
| Backend       | Python                      |
| ML Libraries  | Pandas, Scikit-learn, Joblib|
| Deployment    | Localhost / Streamlit Cloud |

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── model.pkl                       # Trained ML model
├── app.py                          # Main Streamlit application
├── train_model.py                  # Script for training and saving the model
|___ churn_model.py
├── churn_analysis.ipynb            # EDA Notebook
├── requirements.txt                # Project dependencies
└── README.md                       # Project documentation
```

---

## 🔧 How to Run Locally

### 1. Clone the Repository

```bash
git clone https://github.com/23BCE9315/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Train the Model (if model.pkl not present)

```bash
python train_model.py
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

Your app will be available at `http://localhost:8501`.

---

## 🧠 How It Works

- The dataset is cleaned and preprocessed using label encoding.
- A Random Forest Classifier is trained on features like tenure, charges, contract type, etc.
- Streamlit UI collects input from users and uses the trained model to predict churn.

---

## 📸 Screenshots



**🔘 Input Form UI**  
<img width="1918" height="948" alt="Screenshot 2025-08-02 224157" src="https://github.com/user-attachments/assets/f9e5c53c-be91-482d-8c4e-5e55454bf3b9" />
<img width="1916" height="984" alt="Screenshot 2025-08-02 224221" src="https://github.com/user-attachments/assets/72084af7-10f3-442b-ba68-ea439eae320f" />
<img width="1919" height="822" alt="Screenshot 2025-08-02 224236" src="https://github.com/user-attachments/assets/7dd0ee23-3812-401b-a8b5-922856c96dda" />




**📍 Churn Prediction Output**  
<img width="1919" height="262" alt="Screenshot 2025-08-02 224236" src="https://github.com/user-attachments/assets/47da0cab-8e3e-4b7c-8758-b7a76d256b80" />


---

## 🛡️ .gitignore Summary

Include the following in your `.gitignore` file:

```
__pycache__/
*.pkl
.env
*.log
.ipynb_checkpoints/
.DS_Store
```

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🙋‍♀️ Author

- 💼 Developed by Purini Durgamma  
- 🌐 GitHub: [23BCE9315](https://github.com/23BCE9315)

---

## 🌟 Star the Repo

If you found this helpful, don’t forget to ⭐ the repository and share it with others!



