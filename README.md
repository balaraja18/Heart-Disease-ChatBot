# 🫀 AI-Powered Heart Disease Chatbot

## 🚀 Overview

An intelligent healthcare web application that predicts the likelihood of heart disease and provides conversational assistance using machine learning and AI. The system combines predictive analytics with a chatbot interface to deliver user-friendly health insights.

---

## 🧠 Key Features

* 🤖 AI-powered chatbot for symptom-based interaction
* 📊 Machine learning model for heart disease prediction
* ⚡ Real-time predictions using Flask backend APIs
* 🔐 Secure API key handling using environment variables (`.env`)
* 💬 Hybrid system combining ML + conversational AI
* 🌐 User-friendly web interface

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Machine Learning:** Scikit-learn
* **Frontend:** HTML, CSS
* **Environment Management:** python-dotenv
* **AI Integration (Optional):** Groq / OpenAI API

---

## 📂 Project Structure

```
heart-disease-chatbot/
│
├── app.py
├── model.pkl
├── templates/
├── static/
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation & Setup

### 🔹 1. Clone the repository

```
git clone https://github.com/balaraja18/Heart-Disease-ChatBot.git
cd Heart-Disease-ChatBot
```

### 🔹 2. Install dependencies

```
pip install -r requirements.txt
```

### 🔹 3. Setup environment variables

Create a `.env` file:

```
GROQ_API_KEY=your_api_key_here
```

### 🔹 4. Run the application

```
python app.py
```

---

## 🌐 Run Locally

Open your browser and go to:

```
http://127.0.0.1:5000
```

---

## 📸 Screenshots

*(Add screenshots of your UI here for better presentation)*

---

## 🔐 Security

* Sensitive data like API keys are stored using `.env`
* `.env` is excluded using `.gitignore`

---

## 📈 Future Enhancements

* 🌐 Deploy on cloud (Render / AWS / Railway)
* 📊 Add interactive dashboards and visualizations
* 🧠 Improve ML model accuracy
* 🗂️ Store patient history and analytics
* 🤖 Enhance chatbot with advanced LLM capabilities

---

## 👨‍💻 Author

**Bala Raja**

* GitHub: https://github.com/balaraja18

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
