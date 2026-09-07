# <img src="https://github.com/user-attachments/assets/8e80fda9-8162-4f5f-a764-15f2f2d4db37" alt="TaskClock" width=30% height=30%>
TaskClock is a smart scheduling app designed to help students manage their study time efficiently. It features AI-powered scheduling, MCQ-based performance tracking, and leaderboards.

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) [![taskclock-website](https://img.shields.io/badge/taskclock-website-brown?style=for-the-badge)](https://eth4nplays.wixstudio.com/taskclock) [![taskclock-intall](https://img.shields.io/badge/Latest-Releases-green?style=for-the-badge)](https://github.com/Eth4nplays/TaskClock/releases) 

![TC Win](https://github.com/user-attachments/assets/78e7afb0-b7f4-43e5-af9c-f13462e857b3) 

## About this Project
This was a competition project, below are some of the awards achieved:
- InventX Jr. 2025 - 2nd Silver
- Hari Innovasi Negeri Melaka 2025 - First Place for Special Award Secondary School Category
- Hari Innovasi Negeri Melaka 2025 - Gold Medal for Secondary School Category
- KLESF 2025 - Merit
- Malaysian Digital APICTA 2025 - Winner
- APICTA 2025 Kaohsiung - Merit

Special thanks to [RoboForce](https://roboforce.com.my/) for supporting us throughout the year.

## Features
- Automated Scheduling: ​Automated scheduling based on your unavailable times with study reminders.
- Practice & Learn: Practice with our MCQ questions to test your knowledge.
- Leaderboards & XP Rewards: Study and climb the leaderboard and track your progress

## Installation Instructions

Install either the APK or EXE based on your platform in the Releases page, and run the installer.

Aditionally, if you are on Android, install our app by searching "TaskClock" in Google Play Store. (only in Malaysia atm)

## Setup Instructions
*currently the app is still not open-sourced, we are preparing to open-source the app in the near future. 

Note: It is recommended to use your own Firebase project. Firebase now requires App Check enforcement to use their AI Logic features, which is used in this app.

### 1. Clone the Repository
```bash
git clone https://github.com/Eth4nplays/TaskClock.git
cd TaskClock
```

### 2. Install Dependencies
```bash
flutter pub get
```

### 3. Firebase
- Create a Firebase project: https://console.firebase.google.com/

    Set up App Check, Authentication (Email and Password), Remote Config, Cloud Firestore

- Install the Firebase CLI, installing through npm is recommended: https://firebase.google.com/docs/cli#setup_update_cli

    Configure your Firebase project into the Flutter application: https://firebase.google.com/docs/flutter/setup

- Add ```app_check.dart``` in the lib directory and set your ```kWebRecaptchaSiteKey``` inside.

    An example would be:
    ```dart
    const kWebRecaptchaSiteKey = 'site key here';
    ```

    Learn more about how to get the site key here: https://firebase.google.com/docs/app-check/web/recaptcha-enterprise-provider

### 4. Run
```bash
flutter run
```
