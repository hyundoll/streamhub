# streamhub
<div align="center">
Live TV Streaming Platform
  <a href="https://github.com/hyundoll/streamhub/releases/download/Flutter/app-release.apk">
    <img src="https://img.shields.io/badge/⬇️_Download-StreamHub_APK-FF4081?style=for-the-badge&logo=android" alt="Download APK"/>
  </a>
  <a href="https://testflight.apple.com/join/mRB5TeBw">
    <img src="https://img.shields.io/badge/⬇️_Download-StreamHub_iOS_TestFlight-007AFF?style=for-the-badge&logo=apple" alt="Download iOS TestFlight"/>
  </a>
<br><br>
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://github.com/hyundoll/streamhub/releases/download/Flutter/app-release.apk">
<img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://testflight.apple.com/join/mRB5TeBw">

  
  ### Live TV Streaming Platform
  
  [![Flutter](https://img.shields.io/badge/Flutter-3.32+-02569B?style=flat&logo=flutter)](https://flutter.dev)
  [![Platform](https://img.shields.io/badge/Platform-Android-green?style=flat&logo=android)](https://www.android.com)
  [![DVB-I](https://img.shields.io/badge/DVB--I-Compliant-blue?style=flat)](https://dvb.org)
  [![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=flat)](LICENSE)
</div>

---

## 📺 About

**StreamHub** is a Live TV streaming application built with Flutter for mobile devices. This app was specifically developed for the **DVB-I UI Competition**, implementing the DVB-I specification for service discovery and programme metadata.

The application follows the **DVB-I standard** as defined in:
> [DVB BlueBook A177r7 - Service Discovery and Programme Metadata for DVB-I (TS 103 770 v1.3.1)](https://dvb.org/wp-content/uploads/2024/09/A177r7_Service-Discovery-and-Programme-Metadata-for-DVB-I_Interim-Draft_TS-103-770-v131_July-2025.pdf)


---

## 🎥 Demo Video

▶️ (https://youtu.be/XP8xFTzcacI)

---

## ✨ Features

- 📡 **DVB-I Compliant** - Implementation of DVB-I service discovery
- 📺 **Live TV Streaming** - Watch live television channels in real-time
- ⏪ Catch-up TV - Watch previously aired programs on-demand
- 🔁 **Restart TV** - Jump back to the beginning of an ongoing broadcast
- 🎞️ **Boxset Support** - Browse series, seasons, and episodes grouped by Boxset metadata
- 💬 **Subtitle Support** - Display subtitles on live channels
- ⭐ Favorite Channels - Create and customize your own channel list with drag-and-drop reordering
- 🔎 Smart Filtering - Filter live broadcasts by genre, age rating, accessibility, and other supported attributes
- 📑 Channel Management - Organize channels in your preferred order
- 🎨 **Modern UI/UX** - Beautiful and intuitive interface design
- 📱 **Native Android** - Optimized for Android devices
- 🔍 **Service Discovery** - Automatic channel discovery and metadata retrieval
- 📊 **Programme Metadata** - Rich EPG (Electronic Programme Guide) information
- ⚡ **High Performance** - Smooth streaming with minimal latency
- 🖥️ **Cast to TV or Big Screen** - Watch Live content on your TV

---

## 🏆 DVB-I UI Competition

This application is an official submission to the **DVB-I UI Competition**, demonstrating innovation in:

- UI/UX design  
- Programme navigation  
- Enhanced accessibility  
- Support for Boxsets, Restart, Catch-up  
- DVB-I metadata compliance  

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.32.8+)
- Android Studio / VS Code
- Android SDK 36 (API 35) - Fully compatible with Galaxy S25
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
<img width="270" height="585" alt="Screenshot_20260618_135427" src="https://github.com/user-attachments/assets/5e0d83ff-d511-4ffe-a1b3-cddab840d1c7" />
<img width="270" height="585" alt="Screenshot_20260618_135040" src="https://github.com/user-attachments/assets/156d1b9c-fb5a-4869-a9ad-1cb9dc31804f" />
<img width="270" height="585" alt="Screenshot_20260618_135322" src="https://github.com/user-attachments/assets/b5270d75-3183-4175-a747-6b16a949e6c5" />



## 🛠️ Technology Stack

- **Framework**: Flutter
- **Language**: Dart
- **Platform**: Android / iOS (Please email me if you want to download the iOS app)
- **Streaming**: ExoPlayer / BetterPlayer

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

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

## 👥 Authors

- **Hyunmin Jeon** - *Initial work* - [https://github.com/hyundoll](https://github.com/hyundoll)

---

## 🙏 Acknowledgments

- DVB Project for the DVB-I specification
- Flutter community for excellent resources

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
