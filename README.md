# AI-Driven-C-Section-Wound-Monitoring-System-for-Postoperative-Maternal-Health-


#  AI-Powered C-Section Wound Classification App

This project provides a complete machine learning pipeline and mobile interface for detecting **C-section wound infections** using **Convolutional Neural Networks (CNNs)**. The app allows mothers to take a picture of their wound and receive a real-time classification as either **Healthy** or **Infected**.

---

## 🔗 GitHub Repository
👉 [GitHub Repo Link Here](https://github.com/Esther-Mbanzabigwi/AI-Driven-C-Section-Wound-Monitoring-System-for-Postoperative-Maternal-Health-.git)

---

## ⚙️ Setup Instructions

### 🐍 Python Environment Setup
1. Clone the repo:
```bash
git clone https://github.com/Esther-Mbanzabigwi/AI-Driven-C-Section-Wound-Monitoring-System-for-Postoperative-Maternal-Health-.git
cd your-wound-classification-project
```

2. Create virtual environment and activate it:
```bash
python3 -m venv venv
source venv/bin/activate  # or `venv\Scripts\activate` on Windows
```

3. Install requirements:
```bash
pip install -r requirements.txt
```

4. Run Flask API backend:
```bash
python wound_api_backend.py
```

###  Flutter Setup
1. Install Flutter and Android Studio
2. Open the `/flutter_app/` directory in your Flutter IDE
3. Connect to your phone/emulator and run:
```bash
flutter run
```

4. Make sure the `baseURL` in the app matches the IP address of your backend

---

## 🎨 Designs & Screenshots

### ✅ Mobile App Wireframes (Flutter)
- Included in `designs/wireframes/`
- Format: `.png` screenshots and `.fig` files for Figma

###  Model Diagrams
- CNN Architecture
- System Architecture
- Data Flow Diagram
- Entity-Relationship Diagram
- Use Case Diagram

All visuals are in the `/designs/` folder.

---

## 🚀 Deployment Plan

### Backend (API):
- Hosted using **Render** or **Railway**
- Public `/predict` endpoint for Flutter integration

### Frontend (Mobile App):
- Built with Flutter
- Compatible with Android and iOS
- Users upload wound images and receive real-time predictions

---

## 📹 Demo Video
- 📼 Link: [Upload to YouTube or Google Drive and paste here]
- Duration: ~7 minutes
- Includes:
  - CNN Training Overview
  - Mobile App Walkthrough
  - Flask API Integration
  - End-to-end prediction demonstration

---

##  ML Code Components

- `cnn_model.py` — Custom CNN architecture
- `train_model.ipynb` — Kaggle training notebook
- `wound_api_backend.py` — Flask API
- `flutter_app/` — Mobile Flutter code

---

## 📂 Folder Structure
```
├── wound_api_backend.py
├── wound_model.pth
├── train_model.ipynb
├── README.md
├── requirements.txt
├── designs/
│   ├── architecture_diagram.png
│   ├── wireframe.png
│   └── ...
├── flutter_app/
│   ├── lib/
│   ├── assets/
│   └── main.dart
```

---

## 🙏 Acknowledgments
- Dataset Source: [UWM BIGDATA GitHub Dataset](https://github.com/uwm-bigdata/wound-classification-using-images-and-locations)
- Inspired by maternal health challenges in Rwanda

---

