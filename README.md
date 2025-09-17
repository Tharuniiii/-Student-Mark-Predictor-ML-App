# -Student-Mark-Predictor-ML-App
This project is a simple Machine Learning web application built using Flask. The app predicts the marks a student can achieve based on the number of study hours they input. It demonstrates the end-to-end process of training a regression model, saving it, and deploying it into a web application with an interactive UI.

# 📌 Features

User-friendly interface to enter study hours.

ML model trained to predict student marks.

Flask backend to handle requests and predictions.

CSS-styled responsive UI for a professional look.

Banner and modern card-style design.

# 🛠️ Tech Stack

Python

Flask

HTML / CSS

Scikit-learn (for ML model)

Pickle/Joblib (for model persistence)

# ⚙️ How It Works

1.Model Training:

The dataset (study_hours vs marks) is used to train a Linear Regression model.

The trained model is saved as a .pkl file using pickle.

2.Web Application:

Flask handles routes and integrates the trained model.

User enters the number of study hours in the form.

The backend loads the trained model and predicts the marks.

Prediction is displayed dynamically on the web page.

# 📂 Project Structure
Student-Mark-Predictor/
│
├── static/
│   └── images/
│       └── college_banner2.png       # Banner image
│
├── templates/
│   └── index.html                    # Frontend HTML with CSS
│
├── model.pkl                          # Trained ML model
├── app.py                             # Flask backend
├── requirements.txt                   # Dependencies
└── README.md                          # Project Documentation

# 🚀 Getting Started
1️⃣ Clone the repository
git clone https://github.com/your-username/student-mark-predictor.git
cd student-mark-predictor
2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the Flask app
python app.py
5️⃣ Open in browser
Visit: http://127.0.0.1:5000/

# 🖼️ Screenshot
<img width="1614" height="915" alt="Screenshot 2025-09-17 184923" src="https://github.com/user-attachments/assets/89f50965-951a-4869-a729-6eb261a3f77d" />

# 📊 Example Prediction
Input: Study Hours = 8

Output: Predicted Marks ≈ 80%

# 🔮 Future Enhancements
Add support for multiple features (sleep hours, attendance, etc.).

Store past predictions in a database.

Deploy on Heroku / Render / AWS / Azure.

Add dark mode toggle for UI.

👩‍💻 Author

Tharuni T
Undergraduate | AI & ML Enthusiast 🚀
