Here’s your **Phase 5: Multiplatform Deployment** transformed into a **1-Week Bootcamp Course** that walks you through daily instructions, practical tasks, and curated resources so you can confidently prepare your game for PC, iOS, and Android.

---

# 🚀 Unity Bootcamp – Phase 5: **Multiplatform Deployment**

**Project:** *Astralore: Crossworld Demo*
**Goal:** Build, test, optimize, and deploy your Unity game on PC, Android, and iOS

---

## 🔗 Quick Navigation

* [Day 1 – Platform Setup (PC, Android, iOS)](#day-1--platform-setup-pc-android-ios)
* [Day 2 – Touch Input + Virtual Joystick](#day-2--touch-input--virtual-joystick)
* [Day 3 – Responsive UI & Safe Areas](#day-3--responsive-ui--safe-areas)
* [Day 4 – Platform Detection + Input Switching](#day-4--platform-detection--input-switching)
* [Day 5 – Optimization for Mobile Devices](#day-5--optimization-for-mobile-devices)
* [Day 6 – Build + Run on Devices](#day-6--build--run-on-devices)
* [Day 7 – Polish, QA, and Distribution Prep](#day-7--polish-qa-and-distribution-prep)

---

## 📅 **Day 1 – Platform Setup (PC, Android, iOS)**

### ✅ Goals:

* Prepare Unity to build on PC, Android, and iOS.

### 📚 Tutorials:

* ▶️ [Build for PC/Mac/Linux – 7 min](https://youtu.be/vjfwvjLKwME)
* ▶️ [Android Setup in Unity – 10 min](https://youtu.be/sNhy8vZc3n4)
* ▶️ [iOS Build & Apple Dev Setup – 8 min](https://youtu.be/oVynpntTj1I)

### 🛠 Tasks:

* Install Android SDK & NDK from Unity Hub
* Link your Apple Developer account via Xcode
* Create a basic PC build (`.exe` or `.app`) from your project

---

## 📅 **Day 2 – Touch Input + Virtual Joystick**

### ✅ Goals:

* Add mobile touch input using a virtual joystick.

### 📚 Tutorials:

* ▶️ [Touch Input & Virtual Joystick – 12 min](https://youtu.be/BY3qvBO7PbA)
* ▶️ [Joystick Pack Setup – 8 min](https://youtu.be/xb3xG0X_PBQ)

### 🛠 Tasks:

* Import [Joystick Pack (Free)](https://assetstore.unity.com/packages/tools/input-management/joystick-pack-107631)
* Create a `MobileInputManager.cs` to handle `Input.touchCount`, `TouchPhase`, or Input System touch events
* Update your player movement to support mobile controls

---

## 📅 **Day 3 – Responsive UI & Safe Areas**

### ✅ Goals:

* Ensure UI works across devices and respects safe areas (iPhone notches, etc.)

### 📚 Tutorials:

* ▶️ [Canvas Scaler + Anchors – 10 min](https://youtu.be/2jTY11Am0Ig)
* ▶️ [Safe Area Implementation – 7 min](https://youtu.be/c3pYPIwrRcQ)

### 🛠 Tasks:

* Set `Canvas Scaler` to “Scale with Screen Size”
* Use `Screen.safeArea` to reposition UI elements within bounds
* Test in Unity’s [Device Simulator](https://docs.unity3d.com/Packages/com.unity.device-simulator@latest)

---

## 📅 **Day 4 – Platform Detection + Input Switching**

### ✅ Goals:

* Show/hide input systems (joystick vs keyboard) depending on platform.

### 📚 Tutorials:

* ▶️ [Detect Platforms in Unity – 6 min](https://youtu.be/N_Nb9nCXX7U)
* ▶️ [Input Abstraction Strategy – 11 min](https://youtu.be/BZf1q6wKSZQ)

### 🛠 Tasks:

* Create a `PlatformManager.cs` using `Application.platform`
* If PC: Show WASD + mouse
* If Mobile: Show virtual joystick
* Hook into your input logic to enable platform switching

---

## 📅 **Day 5 – Optimization for Mobile Devices**

### ✅ Goals:

* Improve performance on mobile through batching, compression, and pooling.

### 📚 Tutorials:

* ▶️ [Mobile Optimization Tips – 12 min](https://youtu.be/d3t5aU94dtA)
* ▶️ [Object Pooling in Unity – 10 min](https://youtu.be/tdSmKaJvCoA)

### 🛠 Tasks:

* Use Sprite Atlases or Unity Sprite Packer
* Apply texture compression (ETC for Android, PVRTC for iOS)
* Add `Application.targetFrameRate = 60;`
* Pool UI buttons, projectiles, or frequently spawned objects

---

## 📅 **Day 6 – Build + Run on Devices**

### ✅ Goals:

* Test actual builds on PC, Android, and iOS.

### 📚 Tutorials:

* ▶️ [Build Android .apk/.aab – 8 min](https://youtu.be/f1p1VqKjFR4)
* ▶️ [Build iOS .ipa for TestFlight – 9 min](https://youtu.be/MvS5lR0jFDs)
* ▶️ [Unity Remote Testing – 5 min](https://youtu.be/OTFTKH2VJD8)

### 🛠 Tasks:

* Build `.apk` and install on Android
* Build `.ipa` and deploy via Xcode to iPhone
* Test with Unity Profiler and Device Simulator

---

## 📅 **Day 7 – Polish, QA, and Distribution Prep**

### ✅ Goals:

* Final testing, polish scenes, and prepare for app distribution.

### 📚 Tutorials:

* ▶️ [Polish & Final Touches – 9 min](https://youtu.be/sQZ5_ZF9zYY)
* ▶️ [Publish to Play Store – 11 min](https://youtu.be/v_bfKmmE_IU)
* ▶️ [Publish to App Store – 12 min](https://youtu.be/TpJ7E7UcxYg)

### 🛠 Tasks:

* Add final loading screens, transitions, and pause menu
* Prepare keystore (Android) or provisioning profile (iOS)
* Upload builds to Google Play Console or Apple TestFlight

---

## 📁 Suggested Project Structure

```
/Assets
  /Scripts
    /Input
      PlayerInputController.cs
      MobileInputManager.cs
    /Platform
      PlatformManager.cs
    /UI
      MobileControls.cs
  /Prefabs
    /MobileControls
  /Scenes
    /DemoRegion
  /Plugins
    /Android
    /iOS
```

---

## 🎯 By the End of This Bootcamp, You Will:

✅ Build and run your game on PC, Android, and iOS
✅ Handle both keyboard/mouse and mobile touch inputs
✅ Create UI that scales across devices and respects screen-safe zones
✅ Optimize your game for mobile performance
✅ Submit `.apk` and `.ipa` builds for playtesting or publishing

---