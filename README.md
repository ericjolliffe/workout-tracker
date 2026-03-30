# 🏋️ IRON LOG — Self-Hosted Workout Tracker

A sleek, feature-rich workout tracker that runs entirely in your browser. No accounts, no servers, no subscriptions — just open the file and train.

---

## ✨ Features

### 🗂️ Workout Types
- Create custom workout categories (e.g. *Push Day*, *Leg Day*, *Chest & Triceps*) with color tags for easy identification
- See when each type was last performed at a glance
- Activate a workout type to begin a session

### 💪 Active Workout Logging
- Add exercises from a built-in library of 80+ movements (or create your own)
- Log sets with weight and reps — supports both **lbs** and **kg**
- Inline **last performance reference** shows your previous sets in real time, with a 🔥 PR indicator when you beat your old best
- Live **session volume** display (total weight × reps) updates as you log sets
- Remove individual sets or entire exercises on the fly

### ⏱️ Workout Timer
- Start, pause, and resume a session timer from the header
- Optional **auto-start** on first logged set
- Timer persists across page reloads so you never lose your session

### 📚 Exercise Library
- 80+ pre-loaded exercises across categories: Barbell, Dumbbell, Cable, Bodyweight, Machine, Plyometric, and Cardio
- One-click import of the full library
- Create fully custom exercises with name, category, and target muscle groups
- Search/filter the library by name or category

### 🫀 Muscle Silhouette Visualizer
- Tap any exercise to view an anatomical front/back body diagram with targeted muscles highlighted
- Also available per completed session to review which muscle groups were trained

### 📊 Metrics & Progress Charts
- Per-exercise progress tracking over **1 week / 1 month / 3 months / 1 year / all time**
- Switch between metrics: **Max Weight**, **Total Volume**, **Total Reps**, **Sets**
- Overall **workout volume chart** to track training consistency over time
- Built with [Chart.js](https://www.chartjs.org/)

### 📋 Workout History
- Every completed session is saved with date, duration, volume, sets, and personal notes
- Expandable history cards show a full exercise/set breakdown
- Edit past sessions (date, duration, type, exercises, notes)
- Muscle silhouette view per session

### ⚙️ Settings
- Toggle between **lbs / kg**
- Toggle last-performance hints on/off
- Toggle auto-start timer
- Set body weight for calorie estimation
- Apple Health & Garmin Connect integration hooks (Safari/iPhone)
- **Export** all data as JSON
- **Import** data from a previous export
- Full data reset option

---

## 🚀 Getting Started

No installation required.

1. Download `workout-tracker.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Start logging your workouts

That's it.

---

## 💾 Data & Privacy

All data is stored in your browser's **`localStorage`** — nothing is sent to any server. Your workout data lives entirely on your own device.

To back up or transfer your data, use the **Export All Data (JSON)** button in Settings.

---

## 🛠️ Tech Stack

| Layer | Tech |
|---|---|
| UI & Logic | Vanilla HTML, CSS, JavaScript |
| Charts | [Chart.js 4.4.1](https://www.chartjs.org/) |
| Fonts | [Barlow Condensed, Barlow, JetBrains Mono](https://fonts.google.com/) via Google Fonts |
| Storage | Browser `localStorage` |
| Backend | None |

---

## 📱 Mobile Support

IRON LOG works on mobile browsers. For the best experience on iPhone, open in **Safari** to enable Apple Health integration hooks.

---

## 🤝 Contributing

PRs and issues welcome. Since this is a single-file app, contributions are straightforward — just edit `workout-tracker.html` and submit a pull request.

---

## 📄 License

MIT — free to use, modify, and distribute.
