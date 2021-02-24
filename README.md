# 📳 Lofelt

**Unlock the Power of Haptics in Mobile Devices on Flutter**

**Lofelt** builds state-of-the-art **haptic technologies** for iOS and Android developers and creatives.

## ⚠️ Disclaimer

🖥 This plugin is NOT developed by Lofelt

🍏 This plugin is available only for iOS for the moment

❌ Add Lofelt to your project make it not buildable on Simulator

## ⛏ Getting started

### 🎙 Create .haptic files

To create `.haptic` file from sound, download [Lofelt Studio](https://lofelt.com/downloads) and see [Lofelt Studio documentation](https://developer.lofelt.com)

### 💼 Add .haptic files in your pubspec.yaml

***Example:***
```
 assets:
    - assets/haptics/
``` 

### ⚡️ Init Lofelt in a Widget

```
 await Lofelt.init();
``` 

### ➕️ Load a .haptic file in Lofelt

```
  await Lofelt.load('assets/haptics/test.haptic');
``` 

### ▶️ Play the file !

```
  await Lofelt.play();
``` 

### ⏹ Stop

```
  await Lofelt.stop();
``` 

**To see Lofelt integration with sound, see example**

## 🗺 RoadMap


| Feature | Status |
| ------------- |:-------------:|
| Play .haptic on iOS 🍏 | ✅ |
| Play .haptic on Android 🤖 | ❌ |   
| Unit test Flutter plugin | ❌ |    










