# Flutter
# Health Connect App

A Flutter-based frontend application designed to fetch and display health data (e.g., steps, calories, and heart rate) using a clean and organized architecture.

---

## Features
- Fetch health data from a backend API.
- Display the data in a user-friendly interface.
- Simple and clean architecture with state management using the `Provider` package.

---

## File Structure

```
lib/
├── main.dart
├── models/
│   └── health_data.dart
├── screens/
│   └── home_screen.dart
├── services/
│   └── health_connect_service.dart
├── providers/
│   └── health_data_provider.dart
└── widgets/
    └── health_card.dart
```

### Explanation:
- **`main.dart`**: Entry point of the application. Initializes the app and sets up the home screen.
- **`models/health_data.dart`**: Defines the `HealthData` class, representing the structure of health data.
- **`screens/home_screen.dart`**: Contains the main UI where health data is displayed.
- **`services/health_connect_service.dart`**: Handles API calls to fetch health data.
- **`providers/health_data_provider.dart`**: Manages state using the `Provider` package.
- **`widgets/health_card.dart`**: Reusable widget for displaying health data.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd swe_frontend
   ```

2. **Install Flutter** (if not already installed):
   Follow the [Flutter installation guide](https://flutter.dev/docs/get-started/install).

3. **Install dependencies**:
   ```bash
   flutter pub get
   ```

4. **Run the app**:
   ```bash
   flutter run
   ```

---

## Dependencies

The app uses the following packages:
- `provider`: For state management.
- `http`: For making API requests.
- `google_fonts`: For custom fonts.

Add these dependencies in your `pubspec.yaml` file:
```yaml
dependencies:
  flutter:
    sdk: flutter
  provider: ^6.0.0
  http: ^0.15.0
  google_fonts: ^2.3.0
```

Run the following command to fetch the dependencies:
```bash
flutter pub get
```

---

## Usage

1. Open the app.
2. Press the refresh button to fetch the latest health data.
3. View the displayed stats (e.g., steps, calories, heart rate).

---

## Contributing

1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Screenshots

_Add screenshots of the app interface here._

---

## Contact

For questions or support, please contact:
- **Name**: Your Name
- **Email**: your.email@example.com
