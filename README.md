# Orenda

**Orenda** is a Flutter-based mobile application that demonstrates modern UI design, responsive layouts, and Firebase integration. The project is built to showcase clean architecture, structured navigation, and authentication flows using dummy data, making it ideal for learning and portfolio use.

## Features

* Flutter-based cross-platform mobile app
* Clean and responsive UI inspired by wireframes
* Firebase Authentication (Login & Signup flow)
* Modular screen structure with bottom navigation
* Dashboard and profile screens
* Dummy data integration (safe for testing and learning)
* Scalable project architecture following best practices

##Tech Stack

* **Flutter** (Dart)
* **Firebase**

  * Firebase Authentication
  * Firestore (dummy/sample data)
* **Material Design**

## Project Structure


lib/
│── core/
│   └── routes/
│       └── app_routes.dart
│
│── screens/
│   ├── welcome_screen.dart
│   ├── login_screen.dart
│   ├── home_screen.dart
│   ├── profile_screen.dart
│
│── widgets/
│   └── reusable_widgets.dart
│
│── main.dart

## Setup Instructions

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/orenda.git
   ```

2. Navigate to the project directory

   ```bash
   cd orenda
   ```

3. Install dependencies

   ```bash
   flutter pub get
   ```

4. Configure Firebase

   * Create a Firebase project
   * Add Android/iOS app
   * Generate `firebase_options.dart` using FlutterFire CLI

5. Run the app

   ```bash
   flutter run
   ```

## Purpose

This project is created for educational and portfolio purposes. It helps students and beginner Flutter developers understand app structure, Firebase integration, and UI implementation without using real production data.

## Future Enhancements

* Real-time Firestore integration
* Push notifications
* Advanced state management
* UI animations and transitions

## Author

**Emaan Aarbi**
Computer Science Student | Flutter Developer



