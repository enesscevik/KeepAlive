# KeepAlive

**Automated personal relationship management assistant for Android.**

![Status](https://img.shields.io/badge/Status-Internal_Beta-orange) ![Architecture](https://img.shields.io/badge/Architecture-MVVM-blue) ![UI](https://img.shields.io/badge/UI-Jetpack_Compose-green)

## 🚧 Project Status

This repository hosts the source code for **KeepAlive**, which is currently in an active internal testing phase. To ensure the highest quality standard, the application is being rigorously used and tested in a real-world environment by the developer. The source code will be made publicly available upon the validation of the **v1.0 stable release**.

## 📖 Overview

**KeepAlive** is designed to address the challenge of maintaining personal connections in a fast-paced environment. Unlike traditional "to-do" lists or reminders that require constant manual input, KeepAlive operates on a "self-driving" principle.

The application seamlessly integrates with the Android telephony system to monitor call logs, automatically updating the interaction status for tracked contacts. This ensures that users receive reminders only when necessary, preventing redundant notifications for contacts recently spoken to.

## ✨ Key Features

* **Automated Call Log Synchronization:** Eliminates manual data entry by scanning device call history to update "Last Contact" timestamps intelligently.
* **Dynamic Frequency Management:** Allows users to define specific contact intervals for different individuals, adapting to the unique nature of each relationship.
* **Hybrid Interaction Tracking:** Includes a manual override feature to account for face-to-face meetings or interactions outside of phone calls.
* **Smart Scheduler:**
    * **Self-Correcting Mechanism:** Automatically reschedules reminders if a call is detected before the due date.
    * **Frictionless Action:** Notifications provide direct access to the dialer, minimizing the steps required to initiate a call.
* **Privacy-Centric Design:** Operates entirely offline. All data is stored locally on the device via Room Database, with zero cloud dependency.

The project is built using modern Android development standards and follows the recommended app architecture.

## 📅 Project Lifecycle

The development is structured into distinct phases to ensure stability and scalability.

**Phase 1: Core Implementation (Completed)**
* Implementation of the local database schema and DAO layer.
* Development of the Call Log Manager for background synchronization.
* Construction of the WorkManager infrastructure for periodic checks.

**Phase 2: User Interface & Experience (Completed)**
* Adoption of Material 3 Design principles.
* Implementation of Dark/Light theme support and Dynamic Colors.
* Integration of intuitive animations for seamless navigation.

**Phase 3: Validation & Optimization (Current)**
* Real-world usage testing to identify edge cases in the scheduling logic.
* Battery optimization for background workers.
* Refining the user onboarding flow and permission handling.

**Phase 4: Public Release (Upcoming)**
* Source code publication.
* Contribution guidelines and documentation.

## 🤝 Contact & Contribution

While the code is not yet public, I welcome interest in the project logic or architecture. Please feel free to star the repository to be notified of the official release.

---
*License information will be added upon the public release of the source code.*
