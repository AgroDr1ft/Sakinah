# Sakinah | سَكِينَة

[![Status: Active](https://img.shields.io/badge/Release-Active-10b981?style=for-the-badge&logo=shield)](https://agrodr1ft.github.io/Sakinah/)
[![License: MIT](https://img.shields.io/badge/License-MIT-0284c7?style=for-the-badge)](LICENSE)
[![Dependencies: Zero](https://img.shields.io/badge/Dependencies-Zero-a855f7?style=for-the-badge)]()
[![Privacy: Zero Tracking](https://img.shields.io/badge/Privacy-100%25_Local-f59e0b?style=for-the-badge)]()

**Sakinah** (*Arabic: سَكِينَة — Tranquility, Serenity, Peace of Heart*) is an open-source, non-profit Islamic companion built entirely with modern vanilla web standards. 

Designed as a free, privacy-focused alternative to ad-cluttered commercial mobile applications, Sakinah delivers precise astronomical prayer schedules, mathematical Qibla direction, Quranic recitation, and digital dhikr tools directly in the browser—with zero tracking, zero data harvesting, and zero third-party advertisements.

---

### 🌐 [Launch Sakinah Live](https://agrodr1ft.github.io/Sakinah/)

---

## Features

- **Accurate Global Prayer Times & Countdown**  
  Uses browser geolocation or fallback coordinate registries to fetch daily timings for Fajr, Sunrise, Dhuhr, Asr, Maghrib, and Isha. Includes a real-time second-by-second countdown to the next prayer.
- **Mathematical Qibla Bearing Finder**  
  Calculates the Great-Circle forward azimuth (true bearing) from your exact coordinates to the Holy Kaaba in Makkah ($21.4225^\circ\text{ N}, 39.8262^\circ\text{ E}$) along with geodesic distance tracking via the Haversine formula.
- **Al-Qur'an Reader & Streaming Recitation**  
  Displays full Arabic text in authentic Uthmani script (`Amiri` typography) alongside verified English translations. Includes integrated audio playback with verified reciters.
- **Digital Tasbeeh & Dhikr Counter**  
  Minimalist counter with customizable dhikr presets, persistent session storage, goal thresholds ($33$ / $99$ / $\infty$), and mobile haptic vibration feedback.
- **Daily Reflection & Hijri Date**  
  Automatic calculation and synchronization with the Islamic Lunar (Hijri) calendar paired with daily curated verses.
- **Lightweight & Battery Efficient**  
  Zero frameworks, zero node runtimes, and zero heavy libraries. Runs instantaneously on mobile phones, tablets, and desktop browsers.

---

## Non-Profit & Privacy Pledge

Commercial Islamic utilities have increasingly introduced intrusive full-screen video ads, paid subscriptions, and location trackers. Sakinah was created with a clear non-profit commitment:

1. **No Commercialization:** 100% free and open-source forever. No paywalls, no subscriptions, and no premium tiers.
2. **No Advertising:** Zero banner ads, interstitials, pop-ups, or affiliate links.
3. **Privacy by Default:** Your geographic coordinates are processed locally and sent strictly to open public APIs to calculate prayer times. No database logs your IP, location, or usage habits.

---

## Technical Stack & External APIs

Sakinah relies exclusively on pure, standard web technologies:

- **Frontend:** Semantic HTML5, Modular CSS3 (Custom Variables, Light/Dark theme engine), Vanilla ES6+ JavaScript.
- **Prayer Times & Hijri Calendar:** [Aladhan Public API](https://aladhan.com/prayer-times-api) (Astronomical calculation engines).
- **Quran Text:** [Al-Quran Cloud REST API](https://alquran.cloud/api) (Arabic text and English translations).
- **Audio Recitations:** [QuranicAudio Public CDN](https://quranicaudio.com/) (High-bitrate MP3 streams).
- **Local Storage:** Client-side `localStorage` API for theme preferences and tasbeeh counters.

---

## Local Development & Setup

Sakinah requires no dependencies, node modules, or build steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AgroDr1ft/Sakinah.git
