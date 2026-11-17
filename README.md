# Horizon — OLED Graduation Countdown Lock Screen & Live Wallpaper

![Horizon Cover Preview](cover.jpg)

A responsive, zero-clutter dark-mode countdown utility engineered specifically for **smartphone lock screens** and **desktop live wallpaper engines**. Built on a true OLED black (`#0B0B0E`) canvas with subtle ambient radial lighting, Horizon keeps the top 25% of the viewport completely unobstructed for system clocks and notifications while anchoring your countdown, semester progress, and key graduation milestones in the lower focal zone.

---

## Key Features

- **OLED Dark Mode (`#0B0B0E`)**: Deep charcoal-black canvas with soft radial accent lighting positioned strictly behind the countdown cluster to prevent eye strain and OLED screen burn-in.
- **Top 25% Lock Screen Safe Zone**: Reserves the top `25dvh` completely clear so iOS/Android lock screen clocks, date widgets, and notification banners never overlap UI elements. Includes a built-in **Safe-Zone Preview Toggle** to test clock spacing.
- **Live Tabular Countdown**: High-contrast, jitter-free tabular numerals displaying **Days**, **Hours**, and **Minutes** (with an optional **Seconds** toggle).
- **Final Semester Progress Bar**: Automatically calculates and visualizes the percentage of your final semester completed between your start date and graduation ceremony.
- **Interactive 4-Stage Milestone Timeline**: Track four customizable academic checkpoints (e.g., *Thesis Draft*, *Capstone Demo*, *Final Exams*, *Graduation Day*)—tap any milestone node on screen to toggle completion.
- **Motivational Micro-Quotes**: Subtle footer quote widget that rotates on tap.
- **Pure Wallpaper Mode**: Hides interface chrome for clean lock-screen screenshots or continuous desktop live wallpaper use.
- **Zero Dependencies**: Single self-contained `index.html` file with automatic `localStorage` persistence.

---

## Quick Start & Usage

### 1. Desktop Live Wallpaper (Windows / macOS)
1. Download `index.html`.
2. Open **Lively Wallpaper** (Windows, free), **Wallpaper Engine** (Steam), or **Plash** (macOS).
3. Select **Add Wallpaper** → choose your local `index.html` file (or your live GitHub Pages URL).
4. Click the subtle gear icon in the bottom-right corner to configure your graduation date, degree subtitle, accent color, and enable **Pure Wallpaper Mode**.

### 2. Smartphone Lock Screen (iOS & Android)
1. Open the deployed GitHub Pages link (or local `index.html`) on your phone.
2. Customize your dates and tap **Preview Top 25% Lock Screen Clock** to verify alignment.
3. Enable **Pure Wallpaper Mode**, take a full-screen screenshot, and set it as your Lock Screen wallpaper—or use **iOS Shortcuts** (`Take Screenshot` → `Set Wallpaper`) to auto-refresh daily.

---

## Project Structure

```text
horizon-graduation-countdown/
├── index.html      # Complete standalone application (HTML, CSS, JS)
└── README.md       # Project documentation