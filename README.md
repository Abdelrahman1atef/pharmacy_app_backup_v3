# 💊 Pharmacy App

A comprehensive Flutter-based mobile application for pharmacy management, providing seamless shopping experience for customers and powerful administrative tools for pharmacy owners.

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-3.5.3-02569B?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.5.3-0175C2?logo=dart)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-Private-red)

</div>

---

## 📱 Features

### Customer Features
- 🔐 **Authentication System**
  - Secure login and signup
  - OTP verification
  - Google Sign-In integration
  - Social media authentication

- 🏠 **Home Screen**
  - Product categories browsing
  - Best seller products
  - Featured products display
  - Personalized welcome messages

- 🛍️ **Product Management**
  - Detailed product information
  - Product search functionality
  - Category-based product filtering
  - Product favorites/wishlist

- 🛒 **Shopping Cart**
  - Add/remove items
  - Quantity management
  - Real-time price calculation
  - Persistent cart storage

- 💳 **Checkout System**
  - Multiple payment methods
  - Location selection and delivery address
  - Branch selection
  - Order confirmation

- 📋 **Order History**
  - View past orders
  - Order status tracking
  - Order details review

- 👤 **User Profile**
  - Personal information management
  - Account settings
  - Language selection (English/Arabic)
  - Theme preferences

### Admin Features
- 📊 **Dashboard**
  - Sales analytics
  - Revenue tracking
  - Order statistics

- 📦 **Order Management**
  - View all orders
  - Order status updates
  - Order filtering and search

- 👥 **User Management**
  - User list overview
  - User details view
  - User activity tracking

- 📈 **Reports & Analytics**
  - Business insights
  - Performance metrics

### Technical Features
- 🌍 **Multi-language Support** (English & Arabic)
- 📱 **Responsive Design** - Works on various screen sizes
- 🔔 **Push Notifications** via Firebase Cloud Messaging
- 💾 **Offline Support** with local database (SQLite)
- 🎨 **Material Design 3** UI
- 🗺️ **Google Maps Integration** for location services
- 🔍 **Advanced Search** with debounce and throttling

---

## 🛠️ Tech Stack

### Core Technologies
- **Flutter** - 3.5.3
- **Dart** - 3.5.3

### State Management
- **flutter_bloc** - BLoC pattern for state management
- **Provider** - Dependency injection and state management
- **GetIt** - Service locator for dependency injection

### Backend & Services
- **Firebase Core** - Backend infrastructure
- **Firebase Cloud Messaging** - Push notifications
- **Dio** - HTTP client for API calls
- **WebSocket Channel** - Real-time communication

### Local Storage
- **SQLite (sqflite)** - Local database
- **SharedPreferences** - Key-value storage
- **Path Provider** - File system access

### UI & Design
- **flutter_screenutil** - Responsive UI scaling
- **flutter_svg** - SVG image support
- **Lottie** - Animations
- **Shimmer** - Loading placeholders
- **Animated Toggle Switch** - Interactive UI components

### Additional Packages
- **google_sign_in** - Google authentication
- **google_maps_flutter** - Maps integration
- **url_launcher** - External URL handling
- **share_plus** - Social sharing
- **youtube_player_flutter** - Video playback
- **connectivity_plus** - Network status monitoring
- **easy_localization** - Internationalization
- **persistent_bottom_nav_bar** - Navigation bar

### Code Generation
- **freezed** - Immutable classes and unions
- **json_serializable** - JSON serialization
- **build_runner** - Code generation
- **flutter_gen** - Asset code generation

---

## 📸 Screenshots

### Authentication Screens

<table>
<tr>
<td width="50%">
  
**🔐 Login Screen**
  
<img src="https://github.com/user-attachments/assets/ff5b30ac-8d20-4a21-a108-40d168752845" alt="Login Screen" width="100%"/>

</td>
<td width="50%">
  
**📝 Sign Up Screen**
  
<img src="https://github.com/user-attachments/assets/bb9eafcb-c53f-43ae-ab8c-c6ca360b2bc9" alt="Sign Up Screen" width="100%"/>

</td>
</tr>
</table>

---

### Main Screens

<table>
<tr>
<td width="33.0%">
  
**🏠 Home Screen**
  
<img src="https://github.com/user-attachments/assets/b921255a-f254-4a40-8165-be6ef623a0bc" alt="Home Screen" width="100%"/>

</td>
<td width="33.0%">
  
**📋 Product List**
  
<img src="https://github.com/user-attachments/assets/cfa51b75-c1bc-4b3c-bef4-ba956505e73b" alt="Product List Screen" width="100%"/>

</td>
<td width="33.0%">
  
**📦 Product Info**
  
<img src="https://github.com/user-attachments/assets/22ddaf1d-685c-4f37-b607-79ef9f6e4d2b" alt="Product Info Screen" width="100%"/>

</td>
</tr>
<tr>
<td width="50%">
  
**🛒 Shopping Cart**
  
<img src="https://github.com/user-attachments/assets/def4117a-1501-4375-bded-1a9765e43250" alt="Cart Screen" width="100%"/>

</td>
<td width="50%">
  
**💳 Checkout**
  
<img src="https://github.com/user-attachments/assets/0f67037d-cc8f-4b8d-844b-0ab15d77ca25" alt="Checkout Screen" width="100%"/>

</td>
</tr>
</table>

---

### User Screens

<table>
<tr>
<td width="33.33%">
  
**👤 User Profile**
  
<img src="https://github.com/user-attachments/assets/fccb6065-cdca-4d7b-85bc-507a39dd6b0f" alt="User Info Screen" width="100%"/>

</td>
<td width="33.33%">
  
**📜 Order History**
  
<img src="https://github.com/user-attachments/assets/67edd6fc-290f-4579-9921-90f7e0b10cea" alt="Order History Screen" width="100%"/>

</td>
<td width="33.33%">
  
**⚙️ Settings**
  
<img src="https://github.com/user-attachments/assets/c42cde82-3af8-4b6b-b6ee-83258b0993df" alt="More Screen" width="100%"/>

</td>
</tr>
</table>

---

### Admin Screens

<table>
<tr>
<td width="50%">
  
**🎛️ Admin Main Screen**
  
<img src="https://github.com/user-attachments/assets/e0eb4d9c-8f49-482b-b313-c335312d64b9" alt="Admin Main Screen" width="100%"/>

</td>
<td width="50%">
  
**📦 Admin Orders**
  
<img src="https://github.com/user-attachments/assets/a3168284-57f5-410c-b6f0-ce000bac56d0" alt="Admin Orders Screen" width="100%"/>

</td>
</tr>
<tr>
<td width="50%">
  
**👥 Admin Users**
  
<img src="https://github.com/user-attachments/assets/4815bdf1-21c0-4480-b3dd-be165c59a352" alt="Admin Users Screen" width="100%"/>

</td>
<td width="50%">
  
**📊 User Info**
  
<img src="https://github.com/user-attachments/assets/845f604b-9707-4517-b282-4347067fb3a3" alt="Admin User Info Screen" width="100%"/>

</td>
</tr>
</table>


## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- **Flutter SDK** (3.5.3 or higher)
- **Dart SDK** (3.5.3 or higher)
- **Android Studio** / **VS Code** with Flutter extensions
- **Git**
- **Firebase Account** (for backend services)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Abdelrahman1atef/pharmacy_app_backup_v3.git
   cd pharmacy_app_backup_v3
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add Android app to your Firebase project
   - Download `google-services.json` and place it in `android/app/`
   - For iOS, download `GoogleService-Info.plist` and add it to `ios/Runner/`

4. **Run code generation**
   ```bash
   flutter pub run build_runner build --delete-conflicting-outputs
   ```

5. **Run the app**
   ```bash
   flutter run
   ```

### Building for Production

**Android APK:**
```bash
flutter build apk --release
```

**Android App Bundle (for Play Store):**
```bash
flutter build appbundle --release
```

**iOS (requires macOS):**
```bash
flutter build ios --release
```

---

## 📁 Project Structure

```
lib/
├── app_bloc_providers.dart       # Global BLoC providers
├── main.dart                      # App entry point
├── pharmacy_app.dart             # Main app widget
├── firebase_options.dart          # Firebase configuration
│
├── core/                          # Core functionality
│   ├── common_widgets/           # Reusable UI components
│   ├── config/                    # App configuration
│   ├── db/                        # Database models and helpers
│   ├── di/                        # Dependency injection
│   ├── enum/                      # Enumerations
│   ├── models/                    # Data models
│   ├── network/                   # API clients and services
│   ├── notifications/             # Push notification handling
│   ├── routes/                    # Navigation and routing
│   ├── services/                  # App services
│   └── themes/                    # UI themes and styles
│
├── features/                      # Feature modules
│   ├── admin/                     # Admin panel features
│   ├── cart/                      # Shopping cart
│   ├── checkout/                  # Checkout process
│   ├── details/                   # Product details
│   ├── home/                      # Home screen
│   ├── items_list/                # Product listing
│   ├── login&signup/              # Authentication
│   ├── main/                      # Main navigation
│   ├── search/                    # Search functionality
│   ├── settings/                  # Settings screen
│   ├── splash/                    # Splash screen
│   ├── user/                      # User profile
│   └── user_orders/               # Order history
│
├── app_config_provider/           # App-wide state management
├── utils/                         # Utility functions
├── gen/                           # Generated code (assets, colors, fonts)
├── generated/                     # Generated localization files
└── l10n/                          # Localization source files
```

---

## 🏗️ Architecture

This project follows **Clean Architecture** principles with:

- **BLoC Pattern** for state management
- **Dependency Injection** using GetIt
- **Repository Pattern** for data management
- **Feature-based** folder structure
- **Separation of Concerns** (UI, Logic, Data layers)

---

## 🌐 Localization

The app supports multiple languages:
- **English** (en)
- **Arabic** (ar)

Localization files are located in `lib/l10n/` directory.

---

## 🔒 Security

- Secure authentication with OTP verification
- Firebase security rules
- Encrypted local storage for sensitive data
- Secure API communication

---

## 📝 License

This project is private and proprietary. All rights reserved.

---

## 👨‍💻 Author

**Abdelrahman Atef**

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-Abdelrahman1atef-181717?logo=github)](https://github.com/Abdelrahman1atef)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdelrahman%20Atef-0077B5?logo=linkedin)](https://www.linkedin.com/in/abdelrahman-atef-b1a59b24a)
[![Email](https://img.shields.io/badge/Email-abdelrahmanatef3221%40gmail.com-D14836?logo=gmail)](mailto:abdelrahmanatef3221@gmail.com)

</div>

### About Me

I'm a passionate mobile developer specializing in:
- 📱 **Android** development with **Kotlin** and **Java**
- ✨ **Flutter** & **Dart** for cross-platform development
- 🏗️ **Clean Architecture** and **SOLID principles**
- 🔥 **Firebase** backend services
- 📍 **Mansura University** Graduate

---

## 🤝 Contributing

This is a private project. Contributions are not accepted at this time.

---

## 📞 Contact

For any inquiries or questions, feel free to reach out:

- **GitHub**: [@Abdelrahman1atef](https://github.com/Abdelrahman1atef)
- **LinkedIn**: [Abdelrahman Atef](https://www.linkedin.com/in/abdelrahman-atef-b1a59b24a)
- **Email**: abdelrahmanatef3221@gmail.com

---

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Firebase for backend services
- All package contributors
- Design inspiration from modern pharmacy apps

---

<div align="center">

**Made with ❤️ using Flutter**

⭐ If you find this project interesting, consider giving it a star!

</div>
