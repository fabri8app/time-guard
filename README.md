# TimeGuard - Social Media Addiction Blocker

A powerful Flutter mobile application designed to help users control their social media addiction through smart blocking and motivational features.

## 🎯 Features

- ⏱️ **Smart Timer** - Set custom time durations for blocking apps
- 🚫 **App Blocking** - Automatically block apps and websites
- 📊 **Dashboard** - Real-time screen time statistics
- 💪 **Motivation** - Achievements and streak tracking
- 💸 **Dynamic Pricing** - Increasing unlock costs to deter repeated usage
- 📈 **Analytics** - Weekly usage reports

## 📚 Prerequisites

- Flutter SDK (3.6.0 or higher)
- Dart SDK
- Android SDK / Xcode (for iOS)
- Android Studio / VS Code with Flutter extension

## 🚀 Installation

1. Clone the repository
```bash
git clone https://github.com/fabri8app/time-guard.git
cd time-guard
```

2. Install dependencies
```bash
flutter pub get
```

3. Run the app
```bash
flutter run
```

## 📁 Project Structure

```
lib/
├── main.dart                 # App entry point
├── core/                     # Core utilities
├── presentation/             # UI Screens
├── routes/                   # Navigation
├── theme/                    # App theme
└── widgets/                  # Reusable widgets

android/                       # Android native code
ios/                          # iOS native code
```

## 🔧 Building for Android

### APK Build
```bash
flutter build apk
```

### AAB (App Bundle) Build
```bash
flutter build appbundle
```

## 📝 Environment Setup

Create an `env.json` file in the root directory:

```json
{
  "supabase_url": "YOUR_SUPABASE_URL",
  "supabase_key": "YOUR_SUPABASE_ANON_KEY",
  "stripe_key": "YOUR_STRIPE_PUBLIC_KEY"
}
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 🎓 About

TimeGuard is built with Flutter and Dart for cross-platform mobile development.
