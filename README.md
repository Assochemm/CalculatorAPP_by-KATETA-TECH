# Assochemm — Offline Scientific Calculator

Assochemm is a professional, offline-first scientific calculator app maintained by KATETA TECHNOLOGIES.

Important brand & contact information
- Owner / Repository: `Assochemm` (GitHub account)
- Company: KATETA TECHNOLOGIES
- Project lead: Collinx Yusuf Kateta
- Designed by: Melissa Abisaa and Joan
- Contact (phone / WhatsApp): +255797270480 , +255662074848

Overview
- Offline-only calculator using local SQLite for history (sqflite).
- Scientific functions: trig (sin/cos/tan), log/ln, sqrt, powers, factorial, constants (π, e).
- Memory operations (MC/MR/M+/M-/MS), undo/redo, high-precision decimal arithmetic.
- Dark / Light themes with a cyan professional theme.

License
- This project preserves the original MIT license included in the repository.

Prerequisites (beginner-friendly)
1. Install Flutter (stable) — follow https://flutter.dev/docs/get-started/install
   - Ensure you have Flutter >=3.27.0 and Dart >=3.7.0.
2. Install Android SDK / Android Studio and set up an emulator or enable USB debugging on your Android phone.
3. (Optional) Install adb (Android Debug Bridge) to install APKs from your PC.

Quick start — Clone, build, run
1. Clone the repo

```bash
git clone https://github.com/Assochemm/CalculatorAPP_by-KATETA-TECH.git
cd CalculatorAPP_by-KATETA-TECH
```

2. Get dependencies

```bash
flutter pub get
```

3. Run on a connected Android device (USB debugging) or an emulator

```bash
flutter run --release
```

4. Build APK and install via adb

```bash
flutter build apk --release
adb install -r build/app/outputs/flutter-apk/app-release.apk
```

Signing a release for Play Store (optional)
- To publish on Play Store you must sign the app with your own Keystore. See Flutter docs: https://flutter.dev/docs/deployment/android
- Keep your keystore safe and never commit it to the repo.

Branding and assets
- The repository contains a placeholder for app icon and logo assets under `ios/Runner/Assets.xcassets` and android mipmap folders.
- Add your logo files to those locations and update the asset names if necessary.

Contributing (short)
- Fork the repo, create a feature branch, implement changes, then open a PR.
- Run unit tests: `flutter test`.

Files changed for branding
- Application title and labels updated to **Assochemm**.
- Database filename changed to `assochemm.db` (local SQLite).
- Theme updated to cyan primary colors.
- README, CONTRIBUTING, CONTRIBUTORS, NOTICE added/updated with project branding.

If you are new to Flutter or GitHub and want a step-by-step video-style walkthrough, reply here and I will provide a beginner-friendly guide that covers: installing Flutter, connecting your Samsung phone, building the release, and signing an APK.
