# ISS Pass Notifier 🚀

An Android app built with **Kotlin** and **Jetpack Compose** that notifies users 
5 minutes before the International Space Station (ISS) passes overhead.

## ✨ Features
- Choose between major US cities (extendable to any location)
- Fetches real ISS pass data using [Open-Notify](http://open-notify.org/) with fallback to [N2YO API](https://www.n2yo.com/api/)
- Sends Android system notifications 5 minutes before each pass
- Clean UI built with Material3 + Jetpack Compose

## 🛠 Tech Stack
- **Kotlin**
- **Jetpack Compose (Material3)**
- **Coroutines** for async networking
- **AlarmManager + BroadcastReceiver** for notifications
- **AndroidX libraries** (Compose BOM, Lifecycle, Core-KTX)

## 📷 Screenshots
*(Add emulator/device screenshots here once you run the app)*

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/YOUR-USERNAME/ISSPassNotifier.git
