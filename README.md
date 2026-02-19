```markdown
# Flutter Login UI

A clean and modern login screen built with Flutter. Features a gradient background, form validation, password visibility toggle, "Remember me" checkbox, and social login buttons.

## Features

- ✨ Beautiful gradient background
- 🔐 Email and password validation
- 👁️ Toggle password visibility
- ✅ "Remember me" checkbox with fixed overflow issue
- 🔑 Forgot password and sign up links
- 🌐 Social login buttons (Google, Facebook, Apple)
- 📱 Responsive layout with `SingleChildScrollView`
- ⚡ Loading state with circular progress indicator

## Getting Started

### Prerequisites

- Flutter SDK (>=3.0.0)
- Dart SDK (>=3.0.0)
- Android Studio / VS Code (optional)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flutter-login-ui.git
   ```
2. Navigate to the project folder:
   ```bash
   cd flutter-login-ui
   ```
3. Get dependencies:
   ```bash
   flutter pub get
   ```
4. Run the app:
   ```bash
   flutter run
   ```

## Usage

- Enter a valid email (must contain '@') and password (minimum 6 characters).
- Toggle password visibility with the eye icon.
- Check "Remember me" to persist login (UI only, no actual persistence).
- Tap "Sign In" to simulate a login (2-second delay).
- Use "Forgot Password?" or "Sign Up" to navigate (placeholder actions).

## Code Structure

- `main.dart` – Entry point, app theme, and `LoginScreen` widget.
- `LoginScreen` – Stateful widget containing the entire UI and logic.
- `SocialLoginButton` – Reusable button for social logins.

## Screenshot
<p align="center">
  <img src="https://github.com/Nahida-Jannat/login_ui/raw/master/Blue%20Smartphone%20Promo%20Poster(1).png" alt="Blue Smartphone Promo Poster" width="60%" style="max-width: 500px;">
</p>

## Dependencies

- `flutter/material.dart` – Core Flutter material design widgets.
- No external packages are used.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.



