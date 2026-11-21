# KeyLessBLE 🔑

**Bluetooth Low Energy Motorcycle Keyless System**

KeyLessBLE is an IoT project that explores a motorcycle keyless system using Bluetooth Low Energy (BLE).

The project integrates an ESP32 microcontroller with a Flutter mobile application to enable wireless communication between a smartphone and a hardware device.

## ✨ Features

- BLE device scanning.
- Bluetooth device connection.
- Wireless communication between Flutter and ESP32.
- Keyless control through a mobile interface.
- Connection status monitoring.

## 🛠️ Tech Stack

- **Mobile:** Flutter, Dart
- **Microcontroller:** ESP32
- **Communication:** Bluetooth Low Energy (BLE)
- **Firmware:** Arduino / C++

## 🏗️ System Architecture

```text
Flutter Mobile App
        |
        | Bluetooth Low Energy
        |
        v
ESP32 Microcontroller
        |
        v
Control Output
        |
        v
Motorcycle System
```

## 🚀 Getting Started

### Flutter Application

```bash
flutter pub get
flutter run
```

### ESP32 Firmware

1. Open the firmware project using Arduino IDE.
2. Select the appropriate ESP32 board.
3. Configure the BLE service and characteristic UUIDs.
4. Upload the firmware to the ESP32.

## ⚠️ Safety Notice

This project is intended for educational and experimental purposes. A real motorcycle installation requires proper electrical protection, authentication, fail-safe behavior, and testing.

## 🎯 Project Goals

- Explore BLE communication in IoT applications.
- Integrate mobile applications with microcontrollers.
- Develop a prototype of a wireless motorcycle access system.

## 👨‍💻 Author

Developed by **Nazril Hidayatulloh**.
