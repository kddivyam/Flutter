# Health Connect App

A simple Flutter app that shows health data like steps, calories, and heart rate. This project is beginner-friendly and uses clean code organization.

---

## What This App Does
- Gets health data from an online server (API).
- Displays the data in a simple and easy-to-read design.
- Uses `Provider` for managing app state (don't worry if you don't know it yet, it's easy to learn!).

---

## How the Project is Organized

```
lib/
├── main.dart            // Starts the app
├── models/              // Defines how data looks
│   └── health_data.dart
├── screens/             // App pages
│   └── home_screen.dart
├── services/            // Talks to the server (API)
│   └── health_connect_service.dart
├── providers/           // Manages app state
│   └── health_data_provider.dart
└── widgets/             // Reusable pieces of the UI
    └── health_card.dart
```

### Quick Overview:
- **`main.dart`**: The entry point for the app.
- **`models/`**: Contains a file that describes the structure of the health data.
- **`screens/`**: Contains the main screen that shows the health stats.
- **`services/`**: Handles getting data from the server.
- **`providers/`**: Keeps track of the app's state (e.g., loading data).
- **`widgets/`**: Includes small pieces of the design (like cards for displaying stats).

---

## How to Run This App

1. **Install Flutter**: If you don't have it yet, follow [this guide](https://flutter.dev/docs/get-started/install).

2. **Download the project**:
   ```bash
   git clone <repository-url>
   cd swe_frontend
   ```

3. **Get the required packages**:
   ```bash
   flutter pub get
   ```

4. **Run the app**:
   ```bash
   flutter run
   ```

---

## Important Tools We Used
- **`Provider`**: For managing app state (you'll learn it as you go).
- **`http`**: For talking to the server.
- **`google_fonts`**: For adding custom fonts to the app.

Add these dependencies to `pubspec.yaml`:
```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^6.0.0
  http: ^0.15.0
  google_fonts: ^2.3.0
```

Run this command to fetch the dependencies:
```bash
flutter pub get
```

---

## How to Use the App

1. Open the app on your device or emulator.
2. Tap the refresh button to load the latest health data.
3. View your steps, calories, and heart rate stats!

---

## Want to Help Improve the App?

1. Fork the project on GitHub.
2. Make your changes in a new branch:
   ```bash
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Added a new feature'
   ```
4. Push the branch:
   ```bash
   git push origin my-changes
   ```
5. Open a Pull Request!

---

## Contact Us
If you have any questions or need help, feel free to contact:
- **Your Name**: [Your Email]

Happy coding!


## Contact

For questions or support, please contact:
- **Name**: Divyam Kumar
- **Email**: kddivyam567@gmail.com
