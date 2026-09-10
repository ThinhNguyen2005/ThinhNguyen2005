<div align="center">

# Hi, I'm Thịnh 👋

### Android Developer · Kotlin & Jetpack Compose · On-device AI

<p>
  Information Technology student at <strong>Ho Chi Minh City University of Transport (UTH)</strong><br/>
  building practical Android applications with clean architecture, thoughtful UI/UX,<br/>
  local-first data, and practical AI/ML integration.
</p>

<p><strong>Open to Android Internship / Fresher opportunities.</strong></p>

<p>
  <a href="https://linkedin.com/in/nguyễn-thịnh-b58997355">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:nguyenthinhk52005@gmail.com">
    <img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

## About Me

- 📱 Focused on **Android development with Kotlin and Jetpack Compose**.
- 🏗️ Interested in **software architecture, performance, maintainability, and polished UI/UX**.
- 🤖 Exploring **on-device AI, Computer Vision, and privacy-conscious applications**.
- 🔍 I enjoy understanding how systems work under the hood and turning ideas into practical software.

---

## Featured Projects

### 💰 [NotePay](https://github.com/ThinhNguyen2005/Ghichuchitieu)

A privacy-focused, local-first Android personal finance application designed to keep sensitive financial processing on the device whenever possible.

`Kotlin` `Jetpack Compose` `Room` `ViewModel` `LiteRT-LM` `Android`

**Engineering highlights**

- Uses **Room as the local data layer** for income, expenses, and financial records.
- Implements an **opt-in bank notification pipeline** for automatic transaction capture; TPBank is currently supported.
- Runs spending forecasts, OCR, and an optional **LiteRT-LM advisor on-device** instead of uploading financial data to an external AI service.
- Generates **VietQR-compatible payment payloads** locally for bill splitting.
- Uses lifecycle-aware **ViewModels and StateFlow-oriented UI state** across Compose features.

[View repository →](https://github.com/ThinhNguyen2005/Ghichuchitieu)

---

### 🌾 [Cân Lúa Mobile](https://github.com/ThinhNguyen2005/appCanLua)

An offline-first Android application designed around rice weighing and agricultural workflows in the Mekong Delta.

`Kotlin` `Jetpack Compose` `MVVM` `Clean Architecture` `Hilt` `Room` `Firebase`

**Engineering highlights**

- Built with **MVVM + Clean Architecture + Hilt** and a Room-based local data layer.
- Supports weighing workflows with real-time net-weight calculations for tare, impurities, and moisture.
- Uses **Firestore + WorkManager** for cloud-backed data and synchronization workflows.
- Includes market-price trends, agricultural news, season dashboards, and **Google Maps marker clustering**.
- Integrates an AI assistant through **OpenRouter / Gemini with RAG-style rice-price and agronomy context**.

[View repository →](https://github.com/ThinhNguyen2005/appCanLua)

---

### 🚦 [Traffic Violation Detection](https://github.com/ThinhNguyen2005/Web_NhanDienXe)

A computer vision system for detecting red-light violations and recognizing Vietnamese license plates from traffic videos.

`Python` `YOLOv8` `ByteTrack` `EasyOCR` `OpenCV` `Flask` `SQLite`

**Pipeline**

```text
Traffic Video
     ↓
Traffic-light State Detection
     ↓
YOLOv8 Vehicle Detection
     ↓
ByteTrack Tracking
     ↓
Finite-State Violation Logic
     ↓
License Plate OCR
     ↓
Searchable Violation Database
```

**Engineering highlights**

- Tracks vehicles across frames instead of treating detections independently.
- Uses a **finite-state machine** to model waiting-zone → violation-zone transitions and reduce false positives.
- Prevents duplicate violation records for the same tracked vehicle.
- Automatically uses **CUDA GPU acceleration** when available, with CPU fallback.
- Provides a Flask interface for processing videos, reviewing results, and searching stored violations.

[View repository →](https://github.com/ThinhNguyen2005/Web_NhanDienXe)

---

## In Progress

### 🧠 [Cue — Smart Reminder](https://github.com/ThinhNguyen2005/SmartReminder)

An Android productivity project exploring the concept of a **Personal AI Scheduler** — combining tasks, schedules, reminders, routines, group workflows, and AI-assisted planning.

`Kotlin` `Android` `AI`

Current product direction focuses on natural-language task creation, schedule suggestions, conflict detection, and keeping the user in control of AI-generated changes.

[View repository →](https://github.com/ThinhNguyen2005/SmartReminder)

---

## Core Technologies

### Android

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

`Room` · `Hilt` · `WorkManager` · `MVVM` · `Clean Architecture` · `StateFlow`

### AI & Computer Vision

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)

`YOLOv8` · `ByteTrack` · `EasyOCR` · `LiteRT-LM` · `On-device ML`

### Backend, Data & Tools

![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

`Firebase` · `Room` · `SQLite` · `REST APIs` · `GitHub Actions`

---

## GitHub Activity

<div align="center">

<img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=ThinhNguyen2005&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" />

</div>

---

<div align="center">

### Build · Learn · Improve

<p>
  Interested in Android engineering, local-first applications, and practical AI integration.<br/>
  Feel free to reach out through LinkedIn or email.
</p>

<img alt="Profile views" src="https://komarev.com/ghpvc/?username=ThinhNguyen2005&style=flat-square&label=Profile%20Views" />

</div>
