
# 📉 Customer Churn Prediction App

This is a machine learning web application built with **Streamlit** to predict whether a customer will churn (leave a service) based on their demographic and usage data. The model is trained on the **Telco Customer Churn Dataset**.

---

## 🔍 Features

- Upload and preprocess Telco churn data
- Train a Random Forest model
- Predict churn using a web form
- Visualize churn distribution and feature correlations

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **ML Library**: scikit-learn, pandas, joblib
- **Visualization**: matplotlib, seaborn

---

## 📁 Folder Structure
Customer-Churn-Prediction/
│
├── app.py # Streamlit app
├── churn_analysis.ipynb # EDA notebook
├── train_model.py # Model training script
├── model.pkl # Trained ML model (auto generated)
├── requirements.txt # Python dependencies
├── data/
│ └── WA_Fn-UseC_-Telco-Customer-Churn.csv# Dataset file


---

## 🚀 Quick Start (One Bash Setup)

```bash
# Clone the repository
git clone https://github.com/your-username/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

# Create virtual environment
python -m venv venv

# Activate the virtual environment
# For Windows:
venv\Scripts\activate
# For Linux/macOS:
# source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Train the model (creates model.pkl)
python train_model.py

# Run the app
streamlit run app.py
📸 Screenshots

<img width="1918" height="948" alt="Screenshot 2025-08-02 224157" src="https://github.com/user-attachments/assets/7db8b661-676f-484f-a47e-cdbfc7e9db48" />
<img width="1916" height="984" alt="Screenshot 2025-08-02 224221" src="https://github.com/user-attachments/assets/60c6b615-8909-4151-b965-4952b142b171" />
<img width="1919" height="964" alt="Screenshot 2025-08-02 224236" src="https://github.com/user-attachments/assets/5f78e907-637c-4a1a-b152-6a8d7f0ab23d" />




📌 Dataset Source
Telco Customer Churn Dataset - Kaggle

👤 Author
PURINI DURGAMMA
📧 purinidurga21@gmail.com
🔗  https://github.com/23BCE9315
📃 License
This project is licensed under the MIT License.


---




