# 🎉 Event Organisation App

A **visually stunning, feature-rich Flutter app** that allows users to **host and book events** of any kind — from concerts and weddings to private parties and conferences. Integrated with **Firebase** for seamless backend support, user authentication, data storage, and real-time updates. Includes a **social feed** where users can share images of events and like others' posts.

---

## 📱 Features

### 🔖 Event Management
- **Create/Host Events** with title, date, time, location, and type.
- **Browse and Book Events** created by others.
- **Categories**: Concerts, Weddings, Corporate Events, Birthdays, etc.
- **Event Details Page** with full info, images, and booking button.

### 👥 User Authentication
- Sign up / Sign in using **Firebase Auth** (email/password, Google).
- **User Profile**: View hosted/booked events.

### 🖼️ Posts Section (Social Feed)
- Upload event photos (after event is hosted).
- Like others' posts.
- Real-time feed using **Firebase Firestore**.

### 📦 Backend Integration
- Firebase Auth for login/signup.
- Firebase Firestore for events and posts.
- Firebase Storage for image uploads.
- Firebase Hosting (optional for web version).

### 🎨 UI & UX
- Custom **Flutter UI components** with modern, sleek design.
- Fully **responsive** for mobile and tablet.
- Animations and transitions for smoother experience.

---

## 🚀 Tech Stack

| Tech            | Use Case                      |
|-----------------|-------------------------------|
| Flutter         | UI/Frontend Framework         |
| Firebase Auth   | User Authentication           |
| Firestore       | Realtime Database             |
| Firebase Storage| Image Upload & Hosting        |
| Provider / Riverpod | State Management         |
| Google Maps API | Event Location Selection (optional) |

---

## 🧱 Folder Structure
lib/
│
├── models/ # Data models (User, Event, Post)
├── screens/ # All app screens (Home, Events, Feed, etc.)
├── widgets/ # Reusable widgets (Buttons, Cards, etc.)
├── services/ # Firebase services (auth, db, storage)
├── providers/ # State management
├── utils/ # Constants, helpers
└── main.dart # App entry point

yaml
Copy
Edit

---

## 🛠️ Installation & Setup

### 1. Clone the repo

```bash
git clone https://github.com/sahil00016/event-organisation-app.git
cd event-organisation-app
2. Install dependencies
bash
Copy
Edit
flutter pub get
3. Connect Firebase
Create a Firebase project at Firebase Console

Add Android/iOS app

Download google-services.json (Android) and/or GoogleService-Info.plist (iOS)

Place them in:

android/app/google-services.json

ios/Runner/GoogleService-Info.plist

4. Enable Firebase Services
Firestore

Authentication (Email/Password, Google)

Firebase Storage

5. Run the App
bash
Copy
Edit
flutter run
📸 Screenshots
Add actual screenshots once the app UI is built

Home Page	Event Detail	Social Feed

✅ Todo / Roadmap
 Host/Book Events

 Firebase Auth & Firestore

 Image Upload to Firebase Storage

 Post Feed with Likes

 In-app Notifications

 Chat between host and attendees

 Admin Dashboard (web)

🤝 Contributing
Fork the repo

Create a new branch: git checkout -b feature/your-feature

Commit your changes: git commit -m 'Add feature'

Push to the branch: git push origin feature/your-feature

Open a Pull Request

📃 License
This project is licensed under the MIT License.
