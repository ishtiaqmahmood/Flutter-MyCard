# Mi Card 📇

A sleek, beautiful, and customizable digital business card mobile application built with **Flutter**. Designed to display personal contact information, role title, profile picture, and custom typography in a clean Material Design layout.

---

## ✨ Features

- **Personalized Profile Header**: Displays user avatar image with custom styling and typography.
- **Custom Fonts**: Integrated custom Google Fonts (`Pacifico` for name signature style and `Source Sans 3` for subtitles and contact details).
- **Clean Contact Cards**: Material Cards with quick-glance icons for phone numbers and email addresses.
- **Cross-Platform**: Ready to run on iOS, Android, Web, macOS, Linux, and Windows.

---

## 🛠️ Tech Stack

- **Framework**: [Flutter](https://flutter.dev/) (Dart SDK)
- **UI Architecture**: Material Design widgets (`Scaffold`, `Column`, `CircleAvatar`, `Card`, `ListTile`)
- **Assets & Fonts**: Custom TTF fonts (`Pacifico`, `SourceSans3`) and static image assets

---

## 📁 Project Structure

```text
mi_card/
├── assets/
│   └── images/
│       └── ishtiaq.jpg          # Profile image asset
├── fonts/
│   ├── Pacifico-Regular.ttf     # Custom font for name heading
│   └── SourceSans3-Regular.ttf  # Custom font for text/subtitles
├── lib/
│   └── main.dart                # Application entry point & main UI layout
├── test/
│   └── widget_test.dart         # Widget integration tests
├── pubspec.yaml                 # Dependencies and asset/font configurations
└── README.md                    # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed on your local development machine:

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (v3.0.0 or higher recommended)
- [Dart SDK](https://dart.dev/get-dart)
- An IDE with Flutter plugins (e.g., [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio))
- Android Emulator / iOS Simulator / Connected Device

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/mi_card.git
   cd mi_card
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the application:**
   ```bash
   flutter run
   ```

---

## 🎨 Customization

To adapt this card for your own profile:

1. **Profile Picture**: Replace `assets/images/ishtiaq.jpg` with your own photo and update the path in `lib/main.dart` if the filename changes.
2. **Contact Info & Name**: Edit `lib/main.dart` to update the name (`Ishtiaq Mahmood`), job title (`FLUTTER DEVELOPER`), phone number, and email address.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
