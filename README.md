# 📚 Library Management System
A complete system including:

- 📱 Mobile App (Flutter)
- 🌐 Web App
- 🖥 Backend API (PHP + MySQL)

---

## 📁 Project Structure

library_management/
├── mobile_app/        → Flutter app
├── backend_api/       → PHP APIs + Database
└── web_app/           → Web interface

---

## 🔗 Main Locations

### 📱 Mobile App
/mobile_app

### 🖥 Backend API
/backend_api

### 🌐 Web App
/web_app

---

## 🚀 How to Run

### 1️⃣ Mobile App (Flutter)
cd mobile_app  
flutter pub get  
flutter run

### 2️⃣ Backend (PHP + MySQL)
Copy backend folder to XAMPP:  
C:\xampp\htdocs\library_api

Open in browser:  
http://localhost/library_api/

### 3️⃣ Web Dashboard
Open:  
web_app/index.html

---

## 🔌 API Base URL for Flutter
```dart
const String baseUrl = "http://10.0.2.2/library_api/";
