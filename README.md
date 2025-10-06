# WishListApp 📝

[![Kotlin](https://img.shields.io/badge/Kotlin-1.8.0-blue.svg?logo=kotlin)](http://kotlinlang.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=flat)](https://android-arsenal.com/api?level=24)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A feature-rich Android application built with modern Android development practices to help you manage your wishlists efficiently. Built with Kotlin and Jetpack Compose, this app provides a clean, intuitive interface for tracking items you want to purchase.

## ✨ Features

### Core Functionality
- **Item Management**
  - Add new wishlist items with name, description, price, and priority
  - Edit existing items to update details
  - Delete items you no longer want to track
  - Mark items as purchased when acquired

### User Experience
- **Intuitive UI**
  - Clean, Material Design 3 interface
  - Smooth animations and transitions
  - Responsive layout for all screen sizes
  - Dark/Light theme support

### Advanced Features
- **Search & Filter**
  - Search items by name or description
  - Filter by priority, price range, or purchase status
  - Sort items by name, price, or date added

### Data Management
- **Local Storage**
  - Built with Room Database for reliable data persistence
  - Data is stored locally on the device
  - Automatic data backup with Android's Auto Backup feature

## 🚀 Getting Started

### Prerequisites

- Android Studio Flamingo (2022.2.1) or later
- Android SDK 33 (Android 13) or later
- Kotlin 1.8.0 or later
- Gradle 7.5 or later
- Minimum SDK: 24 (Android 7.0)
- Target SDK: 33 (Android 13)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/WishListApp.git
   cd WishListApp
   ```

2. **Open in Android Studio**
   - Launch Android Studio
   - Select "Open an Existing Project"
   - Navigate to the cloned directory and select it
   - Wait for the project to sync and Gradle to build

3. **Run the app**
   - Connect an Android device or start an emulator
   - Click the "Run" button (green play icon) in Android Studio
   - Select your target device and click "OK"

## 🛠️ Technical Stack

### Core Technologies
- **Kotlin** - Primary programming language
- **Jetpack Compose** - Modern declarative UI toolkit
- **AndroidX** - Latest Android support libraries

### Architecture
- **MVVM (Model-View-ViewModel)** - Clean architecture pattern
- **Repository Pattern** - Single source of truth for data
- **Dependency Injection** - Using Hilt for DI

### Data Layer
- **Room Database** - Local data persistence
- **DataStore** - For storing user preferences
- **Coroutines & Flow** - For asynchronous programming

### UI/UX
- **Material Design 3** - Modern theming and components
- **Navigation Component** - For in-app navigation
- **Coil** - For image loading

## 🏗️ Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/krishhh/mywishlistapp/
│   │   │   ├── data/
│   │   │   │   ├── database/     # Room database and DAOs
│   │   │   │   ├── model/        # Data classes
│   │   │   │   └── repository/   # Data repositories
│   │   │   ├── di/              # Dependency injection modules
│   │   │   ├── ui/
│   │   │   │   ├── components/   # Reusable UI components
│   │   │   │   ├── screens/      # App screens
│   │   │   │   └── theme/       # App theming
│   │   │   └── util/            # Utility classes
│   │   └── res/                 # Resources
│   │       ├── drawable/        # Vector assets
│   │       ├── mipmap/          # App icons
│   │       └── values/          # Colors, strings, styles
```

## 📱 Screens

### Main Screen
- Displays list of wishlist items
- Search and filter functionality
- Floating action button to add new items

### Add/Edit Item Screen
- Form to add or edit wishlist items
- Input validation
- Image upload support

### Item Detail Screen
- Detailed view of selected item
- Options to edit or delete
- Share functionality

## 🧪 Testing

The app includes the following test suites:
- **Unit Tests** - For ViewModels and Use Cases
- **UI Tests** - For testing UI components
- **Instrumentation Tests** - For end-to-end testing

To run tests:
```bash
./gradlew test          # Run unit tests
./gradlew connectedTest # Run instrumentation tests
```

## 📦 Dependencies

### Core
- Kotlin Coroutines
- AndroidX Core KTX
- Lifecycle Components
- ViewModel & LiveData

### UI
- Jetpack Compose
- Material 3 Components
- Accompanist (for additional Compose utilities)

### Data
- Room Database
- DataStore Preferences
- Gson (for JSON parsing)

### Testing
- JUnit 4 & 5
- MockK
- Espresso
- Compose Testing

## 🤝 Contributing

I welcome contributions!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
6. 

## 🙏 Acknowledgments

- [Android Developers](https://developer.android.com/) - For amazing documentation
- [JetBrains](https://www.jetbrains.com/) - For Kotlin and Android Studio
- [Google Codelabs](https://codelabs.developers.google.com/) - For excellent learning resources
- [Material Design](https://material.io/design) - For design guidelines and inspiration
