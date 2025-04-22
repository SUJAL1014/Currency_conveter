# Currency Converter App 

## 📝 Description

Currency Converter App is a modern, feature-rich Flutter application that provides real-time currency conversion capabilities. Built with Flutter and Firebase integration, it offers a seamless and intuitive experience for users to convert currencies from around the world.

## ✨ Features

- **Real-Time Currency Conversion:** Get accurate, up-to-date exchange rates
- **Multi-Currency Support:** Access a comprehensive list of global currencies
- **Smart Search:** Quickly find currencies using the search functionality
- **User-Friendly Interface:** Clean and intuitive design for effortless navigation
- **Firebase Integration:** Secure authentication and real-time data updates
- **Responsive Design:** Works seamlessly across different screen sizes

## 📱 Screenshots

| All Currencies | Converter | Conversion |
|:---:|:---:|:---:|
| ![All Currencies](projectphotos/allcurrency.png) | ![Converter](projectphotos/conver.png) | ![Conversion](projectphotos/conversion.png) |

| Modal Sheet | Search Results |
|:---:|:---:|
| ![Modal Sheet](projectphotos/modalsheet.png) | ![Search Results](projectphotos/searched.png) |

## 🛠️ Technical Requirements

- Flutter SDK >=3.2.3
- Dart SDK
- Firebase account (for authentication and data storage)
- Internet connection for real-time currency rates

## 📦 Dependencies

Major dependencies include:
- `firebase_core: ^2.24.2`
- `firebase_auth: ^4.15.3`
- `cloud_firestore: ^4.13.6`
- `http: ^1.1.0`
- `google_fonts: ^6.1.0`
- `flutter_spinkit: ^5.2.0`
- `intl: ^0.19.0`

## 🚀 Installation and Setup

1. **Clone the Repository**
   ```bash
   git clone [repository-url]
   cd Currency-Converter-App
   ```

2. **Install Dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase Setup**
   - Create a new Firebase project
   - Configure Firebase in the app:
     - Add `google-services.json` for Android
     - Add `GoogleService-Info.plist` for iOS
   - Enable Authentication in Firebase Console
   - Set up Cloud Firestore rules

4. **Run the App**
   ```bash
   flutter run
   ```

## 🔧 Configuration

1. **Android Setup**
   - Minimum SDK version: 21
   - Target SDK version: 33
   - Compile SDK version: 33

2. **iOS Setup**
   - Minimum iOS version: 11.0
   - Configure iOS deployment settings in Xcode

## 💡 Usage

1. **Launch the App**
   - Open the app on your device/emulator

2. **Currency Conversion**
   - Select source currency from the list
   - Choose target currency
   - Enter amount to convert
   - View the converted amount instantly

3. **Search Currencies**
   - Use the search bar to find specific currencies
   - Select from search results

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Firebase for backend services
- All contributors who help improve the app

## 📞 Support

For support, email [your-email] or create an issue in the repository.

---

Made with ❤️ using Flutter
