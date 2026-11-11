# Project Showcase

Mobile applications I have worked on professionally. The source code is private under company confidentiality, so this page describes each product, my role and the technology used.

## 1. MyDriverBook: ELD and HOS Compliance (US trucking)

An ELD-based fleet compliance app for US commercial drivers. It helps drivers comply with FMCSA Hours of Service (HOS) regulations by recording driving activity, vehicle inspections and driver logs through Electronic Logging Devices.

**My role**

- Took over the React Native app at an early stage, when it was live with test accounts only, and brought it to a production product used by 100+ US commercial drivers on Android and iOS
- Integrated vendor ELD SDKs into the native layers on both platforms to communicate with logging devices in real time
- Implemented HOS tracking logic aligned with FMCSA regulations
- Built background services for continuous GPS tracking and driving activity monitoring
- Built the DVIR (Driver Vehicle Inspection Report) module with digital signature capture
- Implemented hybrid ELD + GPS fleet tracking for real-time monitoring
- Designed offline-first sync so logs stay correct through connectivity loss

**Technologies:** React Native, TypeScript, Zustand, Turbo Modules (Java/Kotlin), ELD SDK integration, BLE, WorkManager, Foreground Services, GPS tracking, REST APIs

**Live app**

- App Store: https://apps.apple.com/pk/app/my-driver-book/id6670301563
- Google Play: https://play.google.com/store/apps/details?id=app.mydriverbook.com

## 2. Metro Online: E-Commerce (Metro Cash & Carry)

A large-scale e-commerce app owned by Metro Cash & Carry, with 1M+ Play Store downloads. Customers browse products, place orders and manage deliveries.

**My role**

- Built user-facing modules for product browsing, checkout and ordering
- Upgraded the app from React Native 0.69 to 0.74
- Improved scroll performance by about 30% on low-end Android devices and screen load times by about 20–25%
- Integrated REST APIs for product catalogues, customer accounts and order management
- Implemented biometric authentication (Face ID and fingerprint)
- Used Firebase Analytics and Microsoft Clarity to find drop-off points
- Led Urdu localisation with RTL layout support

**Technologies:** React Native, TypeScript, Redux Toolkit, REST APIs, Socket.IO, Firebase Analytics, Microsoft Clarity, biometric authentication

**Live app**

- App Store: https://apps.apple.com/pk/app/metro-online/id1262899618
- Google Play: https://play.google.com/store/apps/details?id=com.metro.metroestore

## 3. Taxi Driver Safety System (BLE emergency monitoring)

A safety app for taxi drivers that uses BLE beacon devices and phone sensors to trigger emergency alerts and provide real-time monitoring.

**My role**

- Built the BLE integration that detects emergency triggers from beacon devices
- Built a covert emergency alert system that notifies contacts and dispatch
- Implemented background services for continuous driver monitoring
- Optimised UI performance and API synchronisation for real-time updates

**Technologies:** React Native, BLE integration, Redux Toolkit, background services, REST APIs

## 4. Salma: Quran Learning App for Children

An interactive app that helps children learn the Quran through gamified lessons, animations and audio recitations. Currently in testing, pre-release.

**My role**

- Built interactive learning modules in Expo and TypeScript
- Built 20+ complex animations with React Native Reanimated
- Implemented low-latency audio playback for recitations, with background playback
- Implemented in-app voice recording

**Technologies:** React Native, Expo, TypeScript, Reanimated, audio playback and recording

## 5. Food Delivery App

An app for browsing restaurants, placing orders and tracking deliveries in real time.

**My role**

- Built UI components and order management flows
- Integrated APIs for restaurant data, order processing and delivery tracking
- Improved UI performance and API synchronisation

**Technologies:** React Native, JavaScript/TypeScript, Redux, REST APIs
