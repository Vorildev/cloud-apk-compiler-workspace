# S23 Ultra AI Director — Turnkey Android Studio Project

This Android project implements the **Floating AI Photography Director** for the **Samsung Galaxy S23 Ultra (`SM-S918B`)**, integrating real-time scene classification, 3D gyroscope angle reticle, S23 Ultra sensor-tuned exposure recommendations (`0.6x`, `1x 200MP`, `3x 70mm`, `10x 230mm`), and zero-touch auto-dialing via accessibility service.

## Two Ways to Build the Test APK

### Method 1: Instant Cloud Build via GitHub (No Android Studio required!)
1. Create a free repository on [GitHub](https://github.com/new).
2. Unzip this project and push or drag-and-drop all files into your repository.
3. Go to the **Actions** tab on your GitHub repository.
4. The workflow will automatically compile `./gradlew assembleDebug` and produce your installable `app-debug.apk` under **Artifacts** in ~2 minutes!
5. Download the APK directly onto your S23 Ultra and tap to install.

### Method 2: Open in Android Studio
1. Unzip `S23UltraAIDirector_Project.zip`.
2. Open Android Studio -> **File** -> **Open...** -> select the `S23UltraAIDirector` folder.
3. Let Gradle sync.
4. Connect your Galaxy S23 Ultra via USB or Wireless Debugging.
5. Click **Run 'app'** (or **Build** -> **Build Bundle(s) / APK(s)** -> **Build APK(s)**).

## First Run on Samsung Galaxy S23 Ultra
1. Launch the app and tap **Grant 'Appear On Top' Permission**.
2. (Optional) Tap **Enable Auto-Dialer in Accessibility** to allow the app to automatically adjust Pro dials.
3. Tap **Launch AI Overlay & Open Camera**.
4. Grant the one-time Android Screen Capture prompt.
5. Open the native Samsung Camera app (Pro Mode or Expert RAW) — the AI HUD will float over your viewfinder, coaching your angle, focal length, and exposure in real time!
