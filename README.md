# ❤️ Heart Disease Prediction App

An interactive **Streamlit web app** that predicts the likelihood of heart disease using a machine learning model (Random Forest Classifier).

---

## 📊 Features

- 🔍 Predicts heart disease (0 = No, 1 = Yes)  
- 📈 Visualizations:
  - Target value distribution
  - Age distribution
  - Chest pain type vs Target
  - Correlation heatmap
- 🧠 Real-time machine learning prediction  
- 🎛️ Clean UI with sliders and dropdowns

---

## 📁 Files in This Repo

| File              | Description                     |
|-------------------|---------------------------------|
| `app.py`          | Main Streamlit web app          |
| `heart.csv`       | Heart disease dataset           |
| `requirements.txt`| Python dependencies             |
| `README.md`       | Project overview                |

---

## 🚀 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/Srimythri26/heart-disease-app.git
cd heart-disease-app

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
Then open http://localhost:8501 in your browser.

📦 Dataset Info
Includes 13 clinical features:
age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal

Target column:

0 → No heart disease

1 → Heart disease present

🛠 Built With
Streamlit

scikit-learn

pandas

matplotlib

seaborn

👩‍💻 Author
Kotra Srimythri
B.Tech CSE | Bhoj Reddy Engineering College for Women
💡 Machine Learning | 💻 Python | 🌐 Web Dev

⭐ Show Support
If you found this useful, please ⭐ star the repo to support the project!
