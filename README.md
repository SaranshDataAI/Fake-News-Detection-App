# 📰 Fake News Detection - Flutter + Flask ML App

A complete end-to-end **Fake News Detection App** built using:
- 🔍 **Machine Learning (Python + Flask)**
- 📱 **Flutter (Frontend UI)**
- 🔗 API-based communication between mobile app and ML backend

---

## 📌 Project Overview

This project detects whether a news article is **real or fake** based on its **headline and body text** using a trained machine learning model.

- 💬 Clean UI built in Flutter
- ⚙️ Backend using Flask API with scikit-learn ML model
- 📂 Deployed locally and ready to host online

---

## 🧠 Machine Learning Model

- ✅ Dataset: 4,009 news articles with `Headline`, `Body`, and `Label (0=Real, 1=Fake)`
- ✅ Preprocessing: Lowercasing, punctuation removal, null handling
- ✅ Vectorizer: `TfidfVectorizer`
- ✅ Model: `Logistic Regression`
- ✅ Accuracy: **96%**

---

## 📁 Project Structure

Fake-News-Detection-App/ ├── Flutter-App/ │ ├── lib/ │ │ ├── home.dart │ │ ├── home_controller.dart │ │ └── main.dart │ ├── pubspec.yaml │ └── ... ├── Flask-API/ │ ├── app.py │ ├── model.pkl │ ├── vectorizer.pkl │ └── ... ├── README.md


---

## 🚀 How to Run

### 🧪 1. Run Flask Backend

```bash
cd Flask-API/
python app.py

cd Flutter-App/
flutter pub get
flutter run

pip install flask scikit-learn pandas joblib

dependencies:
  get: ^4.6.5
  http: ^0.13.6


---

Let me know if you want a version with images/screenshots linked, or if you’d like a `.md` file download version or PDF ready-to-go!
