# streamhub
<div align="center">
Live TV Streaming Platform
  <a href="https://github.com/hyundoll/streamhub/releases/download/Flutter/app-release.apk">
    <img src="https://img.shields.io/badge/⬇️_Download-StreamHub_APK-FF4081?style=for-the-badge&logo=android" alt="Download APK"/>
  </a>
<br><br>
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://github.com/hyundoll/streamhub/releases/download/Flutter/app-release.apk">

  
  ### Live TV Streaming Platform
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.0+-02569B?style=flat&logo=flutter)](https://flutter.dev)
  [![Platform](https://img.shields.io/badge/Platform-Android-green?style=flat&logo=android)](https://www.android.com)
  [![DVB-I](https://img.shields.io/badge/DVB--I-Compliant-blue?style=flat)](https://dvb.org)
  [![License](https://img.shields.io/badge/License-MIT-yellow?style=flat)](LICENSE)
</div>

---

## 📺 About

**StreamHub** is a Live TV streaming application built with Flutter for Android devices. This app was specifically developed for the **DVB-I UI Competition**, implementing the DVB-I specification for service discovery and programme metadata.

The application follows the **DVB-I standard** as defined in:
> [DVB BlueBook A177r7 - Service Discovery and Programme Metadata for DVB-I (TS 103 770 v1.3.1)](https://dvb.org/wp-content/uploads/2024/09/A177r7_Service-Discovery-and-Programme-Metadata-for-DVB-I_Interim-Draft_TS-103-770-v131_July-2025.pdf)

---

## ✨ Features

- 📡 **DVB-I Compliant** - Implementation of DVB-I service discovery
- 📺 **Live TV Streaming** - Watch live television channels in real-time
- ⏪ Catch-up TV - Watch previously aired programs on-demand
- ⭐ Favorite Channels - Create and customize your own channel list with drag-and-drop reordering
- 🔎 Smart Filtering - Filter live broadcasts by genre, age rating, accessibility, and other supported attributes
- 📑 Channel Management - Organize channels in your preferred order
- 🎨 **Modern UI/UX** - Beautiful and intuitive interface design
- 📱 **Native Android** - Optimized for Android devices
- 🔍 **Service Discovery** - Automatic channel discovery and metadata retrieval
- 📊 **Programme Metadata** - Rich EPG (Electronic Programme Guide) information
- ⚡ **High Performance** - Smooth streaming with minimal latency

---

## 🏆 DVB-I UI Competition

This application was created as an entry for the **DVB-I UI Competition**, demonstrating innovative user interface design and user experience for DVB-I compliant streaming services.

### Competition Goals
- Showcase best practices in DVB-I implementation
- Deliver exceptional user experience for live TV streaming
- Demonstrate innovative UI/UX design patterns
- Prove compliance with DVB-I technical specifications

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.0 or higher)
- Android Studio / VS Code
- Android SDK (API level 21+)
- Dart SDK (included with Flutter)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/hyundoll/streamhub.git
   cd streamhub
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

### Build APK

```bash
flutter build apk --release
```

---

## 📱 Screenshots

<img width="270" height="585" alt="Screenshot_20251031_165625" src="https://github.com/user-attachments/assets/b27b3689-956b-4984-9921-5ae4cb68a23e" />

<img width="270" height="585" alt="Screenshot_20251031_165758" src="https://github.com/user-attachments/assets/1447c4d2-fa4c-4034-89d5-76b64ae6f41d" />

<img width="270" height="585" alt="Screenshot_20251031_165816" src="https://github.com/user-attachments/assets/5ba32b10-712f-4dfa-8d65-0c128be03f02" />
<img width="270" height="585" alt="Screenshot_20251031_170117" src="https://github.com/user-attachments/assets/c9a1d248-834a-423d-a167-f192881b782e" />
<img width="270" height="585" alt="Screenshot_20251031_170615" src="https://github.com/user-attachments/assets/c7a4baec-4934-40d8-ad89-a974ca0b0507" />
<img width="270" height="585" alt="Screenshot_20251031_170801" src="https://github.com/user-attachments/assets/d0e608bb-a7da-4640-a351-7d14519e0080" />
 


## 🛠️ Technology Stack

- **Framework**: Flutter
- **Language**: Dart
- **Platform**: Android
- **Architecture**: Clean Architecture
- **State Management**: Provider / Riverpod
- **Networking**: HTTP / Dio
- **Streaming**: Video Player / ExoPlayer

---

## 📋 DVB-I Implementation

StreamHub implements the following DVB-I specifications:

### Service Discovery
- Service List Discovery
- Service List Registry
- XML-based service lists
- Dynamic service updates

### Programme Metadata
- EPG data retrieval
- Schedule information
- Content descriptions
- Programme parental ratings and genre
- Accessiility
- More Episodes
- Restart

### Compliance
- XML schema validation
- Proper namespace handling
- Metadata parsing and display

---

## 🎨 Design Philosophy

StreamHub follows modern design principles:

- **Dark Theme**: Easy on the eyes for extended viewing
- **Gradient Accents**: Vibrant pink, purple, and blue gradients
- **Intuitive Navigation**: Simple and straightforward user flows
- **Responsive Design**: Adapts to different screen sizes
- **Accessibility**: High contrast and readable typography

---


## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Hyunmin Jeon** - *Initial work* - [https://github.com/hyundoll](https://github.com/hyundoll)

---

## 🙏 Acknowledgments

- DVB Project for the DVB-I specification
- Flutter community for excellent resources
- All contributors and testers

---

## 📞 Contact

For questions or support, please contact:

- **Email**: hyunmin.jeon@lge.com
- **LinkedIn**: [https://linkedin.com/in/hyunmin-jeon-b4615b21a](https://linkedin.com/in/hyunmin-jeon-b4615b21a)

---

## 🔗 Related Links

- [DVB Project](https://dvb.org)
- [DVB-I Specification](https://dvb.org/wp-content/uploads/2024/09/A177r7_Service-Discovery-and-Programme-Metadata-for-DVB-I_Interim-Draft_TS-103-770-v131_July-2025.pdf)
- [Flutter Documentation](https://flutter.dev/docs)
- [Android Developers](https://developer.android.com)

---

<div align="center">
  Made with ❤️ for the DVB-I UI Competition
  
  ⭐ Star this repository if you find it helpful!
</div>
