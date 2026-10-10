# 🎲 Flutter Dice Roller App

<div align="center">

  <img src="assests/images/dice-6.png" alt="Dice Roller Logo" width="120" />

  <h3>A modern, sleek, and cross-platform dice rolling application built with Flutter & Dart.</h3>

  <p>
    <a href="https://cap-panaka.github.io/Dice-Rolling-App/">
      <img src="https://img.shields.io/badge/🌐_Live_Demo-Try_It_Online-blueviolet?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Demo" />
    </a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" />
    <img src="https://img.shields.io/badge/Dart-3.x-0175C2?style=flat-square&logo=dart&logoColor=white" alt="Dart" />
    <img src="https://img.shields.io/badge/Platform-Web%20|%20Android%20|%20iOS%20|%20Desktop-4CAF50?style=flat-square" alt="Platforms" />
    <img src="https://img.shields.io/github/license/Cap-Panaka/Dice-Rolling-App?style=flat-square" alt="License" />
    <img src="https://img.shields.io/github/stars/Cap-Panaka/Dice-Rolling-App?style=flat-square" alt="Stars" />
  </p>

</div>

---

## 🚀 Live Demo

Experience the app instantly in your browser:

👉 **[Launch Live Web App](https://cap-panaka.github.io/Dice-Rolling-App/)** 👈

> *Note: If you are setting up GitHub Pages for the first time, deploy your web build using `flutter build web --base-href "/Dice-Rolling-App/"`.*

---

## ✨ Features

- 🎲 **Instant Randomization:** Generates true pseudo-random outcomes from 1 to 6 using Dart's `dart:math` library.
- 🎨 **Sleek Aesthetic:** Beautiful, modern gradient background built with customizable linear color palettes.
- ⚡ **Optimized State Management:** Reactive UI updates powered by Flutter's lightweight `StatefulWidget` architecture.
- 📱 **Fully Responsive & Cross-Platform:** Seamlessly adapts to Web, Android, iOS, Windows, macOS, and Linux screen sizes.
- 🧩 **Clean Modular Codebase:** Separated concerns between presentation, layout widgets, and state logic.

---

## 📸 Preview

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Dice 1</b></td>
      <td align="center"><b>Dice 2</b></td>
      <td align="center"><b>Dice 3</b></td>
      <td align="center"><b>Dice 4</b></td>
      <td align="center"><b>Dice 5</b></td>
      <td align="center"><b>Dice 6</b></td>
    </tr>
    <tr>
      <td><img src="assests/images/dice-1.png" width="90" alt="Dice 1" /></td>
      <td><img src="assests/images/dice-2.png" width="90" alt="Dice 2" /></td>
      <td><img src="assests/images/dice-3.png" width="90" alt="Dice 3" /></td>
      <td><img src="assests/images/dice-4.png" width="90" alt="Dice 4" /></td>
      <td><img src="assests/images/dice-5.png" width="90" alt="Dice 5" /></td>
      <td><img src="assests/images/dice-6.png" width="90" alt="Dice 6" /></td>
    </tr>
  </table>
</div>

---

## 🛠️ Tech Stack

- **Framework:** [Flutter](https://flutter.dev/)
- **Language:** [Dart](https://dart.dev/)
- **UI & Design:** Material Design with custom LinearGradient container
- **Target Platforms:** Web, Windows, Android, iOS, Linux, macOS

---

## 📂 Project Architecture

```plaintext
Dice-Rolling-App/
├── assests/
│   └── images/               # High-resolution dice graphics (dice-1 to dice-6)
├── lib/
│   ├── dice_roller.dart       # Interactive stateful dice roller component & logic
│   ├── gradient_container.dart# Reusable linear gradient canvas wrapper
│   ├── styled_text.dart       # Custom reusable typography component
│   └── main.dart              # Application entry point
├── web/                       # Web platform configuration & bootstrap
├── pubspec.yaml               # Project dependencies and asset registry
└── README.md                  # Project documentation & showcase
```

---

## 🏁 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

Make sure you have the Flutter SDK installed on your system:
- [Flutter SDK Installation Guide](https://docs.flutter.dev/get-started/install)
- Dart SDK (bundled with Flutter)
- Chrome / Edge (for Web) or an Android/iOS emulator / physical device

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Cap-Panaka/Dice-Rolling-App.git
   cd Dice-Rolling-App
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the application:**
   - **On Web (Chrome):**
     ```bash
     flutter run -d chrome
     ```
   - **On Desktop (Windows):**
     ```bash
     flutter run -d windows
     ```
   - **On Mobile Emulator / Device:**
     ```bash
     flutter run
     ```

---

## 🌐 Deploying to GitHub Pages

To deploy your own live web build to GitHub Pages:

1. **Build for web with the repository base href:**
   ```bash
   flutter build web --base-href "/Dice-Rolling-App/" --release
   ```

2. **Push the build artifacts to your `gh-pages` branch:**
   ```bash
   git subtree push --prefix build/web origin gh-pages
   ```

3. Go to **Settings > Pages** in your GitHub repository and set the source branch to `gh-pages`. Your app will be live at `https://cap-panaka.github.io/Dice-Rolling-App/`.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  Made with ❤️ by <a href="https://github.com/Cap-Panaka">Cap-Panaka</a>
</div>
