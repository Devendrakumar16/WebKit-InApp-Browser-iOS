# WebKit Browser - Custom In-App Browser in SwiftUI

Lightweight, robust in-app web browser built in SwiftUI wrapping WKWebView, demonstrating navigation controls, loading progress bars, and bidirectional web-view bridging.

---

## 🛠️ Tech Stack & Architecture
`SwiftUI` `WebKit (WKWebView)` `UIViewRepresentable` `Swift`

- **Platform:** iOS 16.0+
- **Language:** Swift 5.10+
- **Framework:** SwiftUI
- **Architecture:** MVVM / Clean Architecture

---

## ✨ Key Features
- Clean SwiftUI bridge to WKWebView via UIViewRepresentable
- Standard browser navigation toolbar (Back, Forward, Refresh, Share)
- Animated page load progress bar and secure HTTPS indicator
- Custom URL validation and error handling screens

---

## 🚀 Getting Started

### Prerequisites
- macOS Sonoma or newer
- Xcode 15.0 or newer
- iOS Simulator or physical device running iOS 16+

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Devendrakumar16/WebKit-InApp-Browser-iOS.git
   cd WebKit-InApp-Browser-iOS
   ```
2. Open the project in Xcode:
   ```bash
   open *.xcodeproj 2>/dev/null || open *.xcworkspace
   ```
3. If CocoaPods is used:
   ```bash
   pod install
   open *.xcworkspace
   ```
4. Select your target simulator (e.g., iPhone 15 Pro) and press `Cmd + R` to build and run!

---

## 👨‍💻 Author
- **Devendra Kumar** ([@Devendrakumar16](https://github.com/Devendrakumar16))

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
