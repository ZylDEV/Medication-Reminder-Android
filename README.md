# Medication Reminder Android App

An Android application to help users manage and remember their medication schedules. Designed to reduce missed doses and improve medication adherence through timely reminders and easy medication tracking.

## Features

- User authentication (Login & Register)
- Medication management (add, edit, delete)
- Daily medication reminders with alarm notifications
- Medication history tracking
- PDF report export (iText 7)
- Simple and user-friendly Material Design UI

## Tech Stack

- Android (Java)
- Gradle (Kotlin DSL)
- Firebase Authentication
- Firebase Realtime Database
- iText 7 (PDF generation)

## Prerequisites

- Android Studio (latest version recommended)
- Java Development Kit (JDK)
- Active internet connection (Firebase requirement)
- Firebase project with Authentication and Realtime Database enabled

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ZylDEV/Medication-Reminder-Android.git
```

### 2. Setup Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project (or use an existing one)
3. Register your Android app with package name `com.example.pengingatobat`
4. Download the `google-services.json` file
5. Place it in the `app/` directory

### 3. Build and Run

1. Open the project in Android Studio
2. Let Gradle sync and download dependencies
3. Run the app on an emulator or physical device (minimum SDK 28)

## Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/pengingatobat/
│   │   │   ├── MainActivity.java        -- Main / splash screen
│   │   │   ├── login.java               -- User login
│   │   │   ├── registrasi.java          -- User registration
│   │   │   ├── home.java                -- Home screen
│   │   │   ├── kelolaobat.java          -- Medication management
│   │   │   ├── riwayat.java             -- Medication history
│   │   │   ├── akun.java                -- Account settings
│   │   │   ├── paduanapk.java           -- App guide
│   │   │   ├── paduanobat.java          -- Medication guide
│   │   │   ├── AlarmPlayer.java         -- Alarm notification handler
│   │   │   └── NotificationActionReceiver.java
│   │   ├── res/
│   │   └── AndroidManifest.xml
│   └── ...
├── google-services.json                 -- (your own Firebase config)
└── build.gradle.kts
```

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Author

**ZylDEV** - [GitHub](https://github.com/ZylDEV)
