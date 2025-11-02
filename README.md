
# 🛍️ All-In-One Shopping App

[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://developer.android.com)
[![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)](https://gradle.org)

A modern Android shopping application built with Kotlin, providing a seamless e-commerce experience.

## 📱 Features

- **Product Catalog** - Browse and search through various products
- **Shopping Cart** - Add and manage items for purchase
- **User Authentication** - Secure login and registration system
- **Order Management** - Track and manage your orders
- **Responsive UI** - Material Design based user interface

## 🛠️ Tech Stack

- **Language**: Kotlin 100%
- **Build System**: Gradle (Kotlin DSL)
- **Architecture**: Modern Android Architecture Components
- **Minimum SDK**: Android 5.0 (API 21) or higher

## 🚀 Getting Started

### Prerequisites

- Android Studio Arctic Fox or later
- Android SDK API level 21 or higher
- Java Development Kit (JDK) 11+

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/PerfectCoder123/All-In-One-Shopping-App.git
   cd All-In-One-Shopping-App
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an existing project"
   - Navigate to the cloned directory
   - Wait for Gradle sync to complete

3. **Build and Run**
   - Connect an Android device or start an emulator
   - Click "Run" (Shift + F10) or use the play button

### Alternative: Install Prebuilt APK

A prebuilt APK (`AIO.apk`) is included in the repository root. Install it using:

```bash
adb install -r AIO.apk
```

## 🏗️ Project Structure

```
All-In-One-Shopping-App/
├── app/                    # Android application module
│   ├── src/main/          # Main source code
│   │   ├── java/          # Kotlin source files
│   │   ├── res/           # Resources (layouts, strings, etc.)
│   │   └── AndroidManifest.xml
│   └── build.gradle.kts   # App-level build configuration
├── gradle/                # Gradle wrapper files
├── build.gradle.kts       # Project-level build configuration
├── settings.gradle.kts    # Project settings
├── gradle.properties      # Gradle properties
└── AIO.apk               # Prebuilt Android package
```

## 🔨 Building from Source

### Debug Build
```bash
./gradlew clean assembleDebug
```

### Release Build
```bash
./gradlew clean assembleRelease
```

The generated APK will be available at:
`app/build/outputs/apk/`

**Windows users:** Use `gradlew.bat` instead of `./gradlew`

## 📊 Code Quality

- **Language**: 100% Kotlin
- **Build System**: Gradle with Kotlin DSL
- **Modern Android Practices**: Following latest Android development standards

## 🤝 Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Notes

- The project uses Gradle Kotlin DSL for modern build configuration
- Prebuilt APK is included for quick testing
- Project follows standard Android application structure

## 👨‍💻 Developer

**PerfectCoder123**  
- GitHub: [@PerfectCoder123](https://github.com/PerfectCoder123)

## 📄 License

This project is open source. Please check the repository for license information.

---

**⭐ Star this repo if you find it helpful!**
