<div align="center">

# 🚗 AutoLedger — Vehicle Control & Fleet Management

**Track every vehicle, fuel-up, service and expense — for one car or an entire fleet. Offline-first, multi-user, multi-language.**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Isar](https://img.shields.io/badge/Isar%20DB-offline--first-6C5CE7?style=flat-square)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F2545B?style=flat-square)
![iOS](https://img.shields.io/badge/iOS-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Web](https://img.shields.io/badge/Web-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

<a href="https://play.google.com/store/apps/details?id=com.developlogix.autoledger&hl=en"><img alt="Get it on Google Play" src="https://img.shields.io/badge/Google_Play-Download_Now-414141?style=for-the-badge&logo=google-play&logoColor=white"/></a>

</div>

> 🔒 **Source code is private** (commercial product). This page is a case study of what I designed and built end to end.

---

## 🎯 The problem

Vehicle owners and small fleet operators juggle fuel receipts, service history, insurance papers, driver assignments and reminders across notebooks, spreadsheets and chat threads. Costs creep up unnoticed, and renewals get missed.

## 💡 The solution

**AutoLedger** is a single app that keeps the whole life of a vehicle in one place — what it costs, what it needs next, and who is using it — with reports that turn the data into decisions.

---

## ✨ Key features

| Feature | What it does |
|---|---|
| 🚘 **Vehicles & fleets** | Manage personal vehicles or whole fleets, including vehicle transfers between owners. |
| 👥 **Drivers & role-based access** | Add drivers and fleet users with role-based permissions. |
| ⛽ **Fuel, service & expense entries** | Fast logging with fuel price tracking and cost-per-distance insights. |
| 🔧 **Components & maintenance** | Track parts and service intervals so nothing is overdue. |
| ⏰ **Smart reminders** | Local notifications and background tasks for service, insurance and document renewals. |
| 📁 **Document vault** | Store registration, insurance and receipts with photos and files. |
| ✅ **Checklists** | Pre-trip and inspection checklists for drivers. |
| 💰 **Budgets** | Set spending limits and monitor them. |
| 📊 **Reports & PDF export** | Charts and shareable PDF reports for owners, accountants or insurers. |
| ☁️ **Backup & restore** | Keep data safe and move between devices. |
| 🏆 **Achievements & calculators** | Gamified milestones plus handy cost and fuel calculators. |
| 🌍 **Localization** | Multiple languages with an in-app language selector. |
| 💎 **Subscriptions & ads** | Pro subscription (RevenueCat) with a rewarded-ad option for free users. |

---

## 🏗️ Architecture & engineering highlights

- **Offline-first** — local **Isar** database so the app is fast and fully usable without a connection, with Firebase sync in the background.
- **Feature-first structure** with 25+ isolated modules (`vehicle · fleet · driver · entry · budget · reminder · report · document · subscription · …`).
- **GetX** for state management, dependency injection and routing.
- **Role-based access control** for fleets, enforced in the app and in Firestore security rules.
- **Sign in with Google and Apple**, with account-deletion flow and web page to meet App Store and Play Store requirements.
- **Background work** via WorkManager and timezone-aware local notifications.
- **Monetization** — RevenueCat subscriptions, AdMob rewarded unlocks and production ad IDs in release builds, built against an AdMob policy compliance review.
- **Multi-platform** — Flutter targets for iOS, Android and web.
- **Serverless backend** — Cloud Functions for secure server-side operations.

## 🧰 Tech stack

**Flutter · Dart · GetX · Isar · Firebase Auth · Cloud Firestore · Cloud Functions · Firebase Storage · FCM · Google & Apple Sign-In · fl_chart · PDF · WorkManager · RevenueCat · AdMob**

---

## 📸 Screenshots & links

<!-- Add screenshots: <img src="screenshots/home.png" width="220"/> -->
📲 **[Download AutoLedger on Google Play](https://play.google.com/store/apps/details?id=com.developlogix.autoledger&hl=en)**
*Screenshots and demo available on request.*

---

## 🤝 Want an app like this?

I build production-ready mobile and web apps — offline-first data, multi-user access, subscriptions and store release — from idea to App Store.

📫 **sibghat.developlogix@gmail.com** · 🌐 **[developlogix.com](https://www.developlogix.com)** · 💼 **[LinkedIn](https://www.linkedin.com/in/sibghat-ullah-baig-4a2812a1)**

<sub>Built by [Develop Logix](https://www.developlogix.com)</sub>
