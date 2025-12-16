# Airpedia - Airplane Ticket Booking App

## Overview
Airpedia is a Flutter-based mobile application designed for booking airplane tickets. This project is developed as part of the CSE-3112: Software Engineering Lab course.

## Features
- User-friendly interface for searching and booking flights
- Firebase integration for authentication and data storage
- Multi-platform support (Android, iOS, Windows, Linux, macOS, Web)
- API logging overlay for debugging

## Technologies Used
- **Flutter**: Cross-platform UI framework
- **Dart**: Programming language
- **Firebase**: Backend services (Authentication, Firestore, etc.)
- **Provider**: State management
- **Flutter ScreenUtil**: Responsive design
- **Other dependencies**: As listed in `pubspec.yaml`

## Installation
1. Ensure you have Flutter installed. Follow the [official Flutter installation guide](https://flutter.dev/docs/get-started/install).
2. Clone the repository:
   ```
   git clone <repository-url>
   cd Airplane-Ticket-Booking-App-main
   ```
3. Install dependencies:
   ```
   flutter pub get
   ```
4. Set up Firebase:
   - Add your Firebase configuration files (`google-services.json` for Android, `GoogleService-Info.plist` for iOS, etc.).
   - Update `lib/firebase_options.dart` with your Firebase project details.
5. Run the app:
   ```
   flutter run
   ```

## Usage
- Launch the app on your preferred platform.
- Search for flights, select options, and complete booking.
- Use the API log overlay button (visible in debug mode) for monitoring API calls.

## Project Structure
- `lib/`: Main application code
- `android/`: Android-specific configurations
- `ios/`: iOS-specific configurations
- `windows/`, `linux/`, `macos/`, `web/`: Platform-specific code
- `assets/`: Images, icons, and other assets
- `test/`: Unit tests

## Contributing
This is a lab project for CSE-3112. Contributions are welcome for improvements or bug fixes. Please follow standard Flutter development practices.

## License
This project is for educational purposes as part of CSE-3112: Software Engineering Lab.

