# Wikipedia Explorer (wiki_browser)

A lightweight, specialized Flutter mobile application designed to browse, save, and share Wikipedia articles directly within a dedicated environment.

## 🚀 Features

* **In-App Web Browsing:** Seamlessly read Wikipedia articles through an embedded `WebView` without leaving the application.
* **Session History Navigation:** Utilize custom back and forward controls in the app bar to navigate your active browsing history.
* **One-Tap Bookmarking:** Save interesting articles to a session-based favorites list using the floating action button.
* **Favorites Manager:** Access a dedicated "Favorite Pages" screen to view all saved URLs and instantly jump back to them.
* **Native Link Sharing:** Instantly package the current article's URL into an email using your device's native mail client.

## 🛠 Technical Stack

* **Framework:** Flutter / Dart
* **Key Dependencies:** 
  * `webview_flutter`: Renders the inline web browser interface.
  * `url_launcher`: Manages the handoff to native OS apps (like the default email client).

## 🏁 Getting Started

This project is a starting point for a Flutter application. To run and build this project yourself:

1. Ensure you have the [Flutter SDK](https://docs.flutter.dev/get-started/install) installed and configured on your machine.
2. Clone this repository.
3. Run `flutter pub get` in your terminal to fetch all required dependencies.
4. Connect a supported device or emulator.
5. Run `flutter run` to build and deploy the application.

---

### Resources for New Flutter Developers

If this is your first time working with Flutter, here are a few resources to get you started:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)
- [Online Documentation](https://docs.flutter.dev/), which offers tutorials, samples, guidance on mobile development, and a full API reference.