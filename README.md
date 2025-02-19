# 📱 MyChatApp - Android Chat Application


A real-time chat application built with **Jetpack Compose**, **Firebase Authentication**, and **Kotlin**. 🚀

## 📌 Features
- ✅ **User Authentication** – Sign up & Log in using Firebase Authentication.
- ✅ **Real-time Messaging** – Send and receive messages instantly.
- ✅ **Group Chat Support** – Join different chat rooms.
- ✅ **Beautiful UI** – Built with **Jetpack Compose**.
- ✅ **Secure** – Messages are linked to user authentication.

---

## ⚙️ Tech Stack
- **Kotlin** – Primary programming language
- **Jetpack Compose** – UI framework
- **Firebase Authentication** – User authentication
- **Firebase Firestore** – Database for real-time messaging
- **MVVM Architecture** – For maintainability and scalability
- **Navigation Component** – Handles screen transitions

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Akash05-kr/MyChatApp.git
cd MyChatApp
```


---


## 2️⃣ Firebase Setup

To use Firebase in your app, follow these steps:

### 🔹 **Step 1: Create a Firebase Project**
1. Go to [Firebase Console](https://console.firebase.google.com/).
2. Click **Create Project**, give it a name, and continue.
3. Once created, click **Continue to Console**.

### 🔹 **Step 2: Add Firebase to Your Android App**
1. Click on **Add app** and select **Android**.
2. Enter your **package name** (same as in `AndroidManifest.xml`).
3. Download the **google-services.json** file.
4. Move the `google-services.json` file to your project's `app/` directory.

### 🔹 **Step 3: Enable Firebase Services**
1. **Enable Firebase Authentication:**
   - Go to **Authentication** in Firebase Console.
   - Click **Sign-in method** → Enable **Email/Password Authentication**.
   
2. **Enable Firebase Firestore:**
   - Go to **Firestore Database**.
   - Click **Create Database**.
   - Choose **Start in Test Mode** (for development).

### 🔹 **Step 4: Add Dependencies**
Open `build.gradle (Project)` and add:
```gradle
classpath 'com.google.gms:google-services:4.3.10'
```
Open `build.gradle (App)` and add:
```gradle
implementation 'com.google.firebase:firebase-auth-ktx'
implementation 'com.google.firebase:firebase-firestore-ktx'
```

At the end of `build.gradle (App)`, apply:
```gradle
apply plugin: 'com.google.gms.google-services'
```

---

## 3️⃣ Build and Run the Project

1. **Open the project** in **Android Studio**.
2. **Sync Gradle** (`File > Sync Project with Gradle Files`).
3. **Run the app** on an **emulator** or **physical device**.

---



---

## 🖼 Screenshots  

| Sign Up Screen | Chat Room List | 
|---------------|---------------|
| ![SignUp](https://github.com/Akash05-kr/MyChatapp/blob/master/signup.jpg) | ![ChatRooms](https://github.com/Akash05-kr/MyChatapp/blob/master/chatroom.jpg) | 


---

## 💡 Contributing
Feel free to contribute by creating a **pull request** or opening an **issue**!  

---

## 📄 License
This project is licensed under the **MIT License**


---
