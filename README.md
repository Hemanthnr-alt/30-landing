# Lock In — Landing Page

**Master the 1% Standard.**

This repository hosts the official landing page and APK distribution for [Lock In](https://github.com/Hemanthnr-alt/Lock-In-Ecosystem), a local-first personal performance app for Android.

<p align="center">
  <a href="https://30-landing.vercel.app/">Live Site</a> · 
  <a href="https://30-landing.vercel.app/lock-in.apk">Download APK</a> · 
  <a href="https://github.com/Hemanthnr-alt/Lock-In-Ecosystem">Source Code</a>
</p>

---

## What is Lock In?

Lock In is a complete offline performance system that combines six core pillars into one app:

1. **Today Agenda** — Unified daily dashboard with tasks, habits, water intake, and nutrition
2. **Atomic Habits** — Boolean, numeric, and fluid habit tracking with streaks, consistency rates, and audio feedback
3. **43-Nutrient Nutrition** — Clinical-grade micronutrient tracking (13 vitamins, 9 minerals, essential lipids) with 2,233+ offline foods
4. **Weight & Photos** — Daily weight logging and transformation photo timeline stored entirely on-device
5. **Focus Timers** — Stopwatch, countdown, HIIT intervals, and Pomodoro with synthesized ambient soundscapes
6. **PDF Reports** — 30-day executive performance dossiers downloadable in light or dark theme

Everything runs locally. No accounts, no cloud, no subscriptions.

---

## Screenshots

<div align="center">

| Today Agenda | Habit Tracker | Nutrition Engine |
| :---: | :---: | :---: |
| <img src="screenshots/today-agenda-light.jpeg" width="240" /> | <img src="screenshots/habits-discipline-tracker-dark.jpeg" width="240" /> | <img src="screenshots/calories-nutrition-macros-light.jpeg" width="240" /> |

| Photos & Weight | Insights | PDF Dossier |
| :---: | :---: | :---: |
| <img src="screenshots/photos-gallery-timeline-light.jpeg" width="240" /> | <img src="screenshots/weekly-insights-analytics-light.jpeg" width="240" /> | <img src="screenshots/executive-pdf-dossier-light-modal.jpeg" width="240" /> |

| Focus Timers | Tasks & Routines | Rewards |
| :---: | :---: | :---: |
| <img src="screenshots/timer-intervals-soundscapes-light.jpeg" width="240" /> | <img src="screenshots/tasks-recurring-routines-dark.jpeg" width="240" /> | <img src="screenshots/rewards-gamification-dark.jpeg" width="240" /> |

</div>

---

## Install

1. Download `lock-in.apk` from the [landing page](https://30-landing.vercel.app/) or directly from this repository
2. Open the downloaded file on your Android device
3. If prompted, allow installation from unknown sources for your browser
4. Launch Lock In

**Requirements:** Android 8.0+ (API 26+). Optimized for Android 14+.

---

## Landing Page

The landing page is a single static HTML file (`index.html`) with:

- Clean minimal design using Inter typeface
- Interactive 3D device mockup with parallax tilt and screen switching
- Feature overview, screenshot gallery with lightbox, and detailed app information
- Direct APK download

Hosted on Vercel at [30-landing.vercel.app](https://30-landing.vercel.app/).

---

## Tech Stack

| Component | Technology |
| --- | --- |
| App Frontend | React 19, Vite 5 |
| Storage | Dexie.js (IndexedDB) — fully offline |
| Native Layer | Capacitor 8 for Android |
| Landing Page | Static HTML, CSS, vanilla JS |
| Hosting | Vercel |

---

## Privacy

Lock In is 100% offline. All user data stays on the device. No accounts, no analytics, no telemetry, no network requests.

---

<p align="center">
  <b>Lock In</b> · Master the 1% Standard<br/>
  <sub>Built with discipline.</sub>
</p>
