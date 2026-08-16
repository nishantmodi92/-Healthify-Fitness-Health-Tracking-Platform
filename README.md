# 🏃 Healthify — Fitness & Health Tracking Platform


<div align="center">

![Android](https://img.shields.io/badge/Android-Platform-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-First-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-UI-4285F4?style=for-the-badge)
![MVVM](https://img.shields.io/badge/MVVM-Architecture-1976D2?style=for-the-badge)

![Clean Architecture](https://img.shields.io/badge/Clean%20Architecture-Production-0F9D58?style=for-the-badge)
![Room](https://img.shields.io/badge/Room-Database-1976D2?style=for-the-badge)
![WorkManager](https://img.shields.io/badge/WorkManager-Background-0D47A1?style=for-the-badge)
![Google Fit](https://img.shields.io/badge/Google%20Fit-Integration-4285F4?style=for-the-badge&logo=googlefit&logoColor=white)
![Hilt](https://img.shields.io/badge/Hilt-DI-009688?style=for-the-badge)

</div>

---

# 📌 Overview

**Healthify** is a modern Android fitness and health-tracking application designed to help users monitor activity data and understand their fitness progress through a clean, responsive and data-driven mobile experience.

The application demonstrates modern Android engineering practices including:

- Kotlin-first development
- Jetpack Compose
- MVVM
- Clean Architecture
- Google Fit API integration
- Room local persistence
- WorkManager background processing
- Kotlin Coroutines
- Kotlin Flow
- Hilt dependency injection

---

# 🎯 Product Goals

Healthify focuses on:

- Activity tracking
- Fitness data aggregation
- Health insights
- Local data persistence
- Background synchronization
- Responsive user experience
- Maintainable Android architecture

---

# ✨ Key Features

## 🏃 Activity Tracking

- Track fitness-related activity
- Display activity summaries
- Organize historical activity data
- Monitor progress over time

## ❤️ Fitness Insights

- Activity summaries
- Fitness trends
- Historical information
- Progress-oriented data presentation

## 📊 Data Visualization

The application can present:

- Daily activity
- Weekly activity
- Historical trends
- Progress summaries

---

# 🔗 Google Fit Integration

Healthify integrates with Google Fit APIs to access supported fitness/activity information.

Typical flow:

```text
Google Fit
     │
     ▼
Fitness Data Source
     │
     ▼
Repository
     │
     ▼
Domain Model
     │
     ▼
ViewModel
     │
     ▼
Jetpack Compose
