# 📱 Sponsored Ads Manager – Client Production Application

🔗 **Live on Amazon Appstore**  
https://www.amazon.com/Ahmed-Mohamed-Bolo-Markting/dp/B0FSDYLWZZ/

---

## 🚀 Overview

**Sponsored Ads Manager** is a production-level Android application developed for a real client and successfully published on the Amazon Appstore.

The system consists of:

- 📱 A User Mobile Application  
- 🖥️ A separate Admin Panel (Dashboard) for campaign management  

The application enables users to manage sponsored advertising campaigns, track updates, and interact with real-time data while ensuring secure authentication and role-based access control.

> ⚠ Due to client confidentiality agreements (NDA), the Admin Panel source code is not publicly available.

---

## 🎯 Project Purpose

The app was built to provide a structured and scalable solution for managing marketing campaigns, allowing different roles (Admin / Expert / Manager) to interact with the system securely and efficiently.

This project demonstrates production-level architecture, real-world deployment, and clean separation of concerns.

---

## 📱 Mobile Application Features

- Firebase Authentication (secure login system)
- Role-based access control
- Real-time campaign updates
- Campaign creation and management
- Data synchronization using Firebase Firestore
- Offline support handling
- Error state management
- Modular UI built with Jetpack Compose
- Clean Architecture implementation
- State management using ViewModel
- Crash-safe handling and performance improvements

---

## 🖥️ Admin Panel (Backend Dashboard)

The Admin Panel is a separate system used by the client’s internal team to:

- Manage campaigns
- Control user permissions
- Monitor campaign performance
- Approve or update campaign data
- Manage system-level settings

The Admin Panel source code is protected under NDA and is not included in this repository.  
Architecture diagrams and structural explanation can be provided upon request.

---

## 🏗️ Architecture & Design

The application follows **Clean Architecture principles** with proper separation between layers:
📦 app (Presentation Layer)
┣ 📂 ui
┣ 📂 viewmodel
┗ 📂 navigation

📦 domain (Business Logic Layer)
┣ 📂 models
┣ 📂 usecases
┗ 📂 interfaces

📦 data (Data Layer)
┣ 📂 remote
┣ 📂 local
┗ 📂 repository


### Architectural Patterns Used

- MVVM
- Repository Pattern
- Dependency Injection
- SOLID Principles
- Modular Code Structure

---

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** MVVM + Clean Architecture
- **Backend:** Firebase Firestore
- **Authentication:** Firebase Auth
- **Concurrency:** Kotlin Coroutines
- **State Management:** ViewModel + StateFlow
- **Build & CI:** GitHub Actions (if enabled)
- **Version Control:** Git

---

## 🔐 Security & NDA Notice

This project was developed for a private client.

- Business logic and core system design are demonstrated here.
- Sensitive APIs, production keys, and Admin Panel implementation are excluded.
- Mock data and safe configurations are used in this public repository.

For technical interviews, architecture walkthroughs, or deeper system explanation, a live demonstration can be provided upon request.

---

## 📈 Responsibilities & Contributions

As the Android Developer on this project, I was responsible for:

- Designing and implementing the mobile UI using Jetpack Compose
- Structuring the project using Clean Architecture
- Implementing authentication & secure role handling
- Integrating Firebase Firestore for real-time synchronization
- Handling offline states and data consistency
- Optimizing performance and crash handling
- Managing deployment & release process on Amazon Appstore

---

## 📊 Production Status

- Successfully published on Amazon Appstore
- Used as a real client solution
- Built with scalability and maintainability in mind
- Designed for future feature expansion
