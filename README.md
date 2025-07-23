# 🎓 Smart Parents - College Management App

**Smart Parents** is a modern college management mobile application built with **Flutter** and **Firebase**. It streamlines communication and operations between students, parents, faculty, and administrators, providing a centralized platform to manage academic information, track progress, and stay updated in real time.

<p align="center">
  <a href="https://github.com/smart-parents/smart_parents.git">
    <img width="300px" src="https://github.com/smart-parents/smart_parents/blob/main/assets/images/Final.png" alt="Smart Parents logo"><br/>
  </a>
</p>

---

## 🚀 Features

- **Role-based Authentication**
  - Separate login/signup for Admin, Faculty, Student, and Parents
  - Secure authentication via Firebase Auth

- **Notice Management**
  - Admins and Faculty can create/manage notices
  - Students and Parents receive real-time updates

- **Class Schedule**
  - View/manage student timetables
  - Faculty can update and broadcast changes instantly

- **Result Management**
  - Faculty can add/update exam results
  - Students and Parents can view marks and performance history

- **Attendance Tracking**
  - Faculty can mark attendance
  - Students and Parents can track daily/monthly attendance

- **Live Location Tracking**
  - Parents can monitor their child’s real-time location via GPS

---

## 🛠️ Tech Stack

- **Frontend:** Flutter (Dart)
- **Backend:** Firebase
  - Authentication
  - Cloud Firestore
  - Firebase Storage
  - Realtime Database (for live location)
- **State Management:** Provider / Riverpod *(choose based on your setup)*
- **Platform:** Android *(iOS coming soon)*

---

## ✅ Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart SDK (bundled with Flutter)
- Android Studio or VS Code
- Firebase account
- Android device/emulator

---

## 🔧 Project Setup

### 1. Clone the Repo

```bash
git clone https://github.com/Dhruvinkatakiya/smart_parents.git
cd smart_parents
```

### 2. Install Dependencies

```bash
flutter pub get
```

### 3. Firebase Setup

- Go to [Firebase Console](https://console.firebase.google.com/)
- Create a new project
- Enable:
  - Authentication (Email/Password)
  - Firestore Database
  - Realtime Database
  - Firebase Storage
- Download `google-services.json` and place it in:
  ```
  android/app/google-services.json
  ```
- Enable Firebase in `android/build.gradle` and `android/app/build.gradle`

### 4. Run the App

```bash
flutter run
```

---

## 📁 Folder Structure

```
lib/
├── models/           # Data models (User, Notice, etc.)
├── screens/          # UI Screens by user role
├── services/         # Firebase integrations
├── widgets/          # Reusable UI components
├── utils/            # Helpers and constants
└── main.dart         # Entry point
```

---

## 🤝 Contributing

We welcome contributions!

1. Fork the repo
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request
---

## 👨‍💻 Author

**Dhruvin Katakiya**  
[GitHub](https://github.com/Dhruvinkatakiya)  
📫 dev.dhruvin.0.1@gmail.com
