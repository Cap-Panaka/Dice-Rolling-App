# 🎲 Dice Roller
 
![Dice Roller](assests/images/dice-5.png)
 
A minimal, interactive dice rolling app built with Flutter & Dart.
 
**🌐 Live Demo:** https://cap-panaka.github.io/Dice-Rolling-App/
 
---
 
## ✨ Features
 
- **Instant Roll:** Random 1–6 dice outcomes with responsive state management.
- **Sleek Aesthetic:** Modern deep-purple gradient with smooth typography.
- **Cross-Platform:** Runs on Web, Mobile, and Desktop.
---
 
## 🛠️ Built With
 
- [Flutter](https://flutter.dev) & Dart
- GitHub Actions + GitHub Pages (automatic deployment)
---
 
## 🚀 Run Locally
 
```bash
git clone https://github.com/Cap-Panaka/Dice-Rolling-App.git
cd Dice-Rolling-App
flutter pub get
flutter run -d chrome
```
 
---
 
## 📦 Build for Web
 
```bash
flutter build web --release --base-href "/Dice-Rolling-App/"
```
 
The output is in `build/web/`.
 
---
 
## 🔄 Deployment
 
Every push to the `master` branch triggers the workflow in
`.github/workflows/deploy.yml`, which builds the Flutter web app and publishes it to GitHub Pages.
 
---
 
Crafted by [Cap-Panaka](https://github.com/Cap-Panaka)
 
