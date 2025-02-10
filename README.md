# Medi_Minder_App
404 Team not Found | Hackathon (Hack Wars) | JGEC- 2025 |

A **Flutter** application integrated with **Firebase** that helps users set medication reminders. This app includes authentication (signup & login) and local notifications.

## Features

- **User Authentication** (Signup & Login with Firebase)
- **Pill Reminder System** (Schedule medication alerts)
- **Local Notifications** (Flutter Local Notifications)
- **Local Storage** (SQLite or Hive for saving reminders)
- **User-Friendly UI** (Simple and intuitive design)

## Screenshots

(Add screenshots of your app here)

## Tech Stack

- **Flutter** (Dart)
- **Firebase Authentication** (Email & Password)
- **Cloud Firestore** (Storing user data)
- **SQLite / Hive** (Local storage for reminders)
- **Flutter Local Notifications** (Sending alerts)

## Installation

### Prerequisites

- Install **Flutter**: [Flutter Setup](https://flutter.dev/docs/get-started/install)
- Set up **Firebase** for Flutter: [Firebase Setup](https://firebase.flutter.dev/docs/overview)

### Clone the Repository

```sh
git clone https://github.com/your-username/pill-reminder-app.git
cd pill-reminder-app
```

### Install Dependencies

```sh
flutter pub get
```

### Configure Firebase

1. Create a Firebase project in the [Firebase Console](https://console.firebase.google.com/).
2. Add an **Android** and **iOS** app.
3. Download the `google-services.json` (for Android) and `GoogleService-Info.plist` (for iOS) and place them in the respective folders.
4. Enable Firebase Authentication (Email/Password) in the Firebase console.

### Run the App

```sh
flutter run
```
