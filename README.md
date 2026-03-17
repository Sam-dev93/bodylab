# BodyLab

Body measurement & weight tracker PWA with AI-powered screenshot reading.

## Features

- **AI Screenshot Scanning** — Upload Arboleaf scale/tape screenshots, Claude reads values automatically
- **Body Silhouette** — Visual body map with measurement indicator lines
- **BMI Auto-calc** — From height (settings) + weight
- **Visceral Fat Estimation** — Waist-to-Height Ratio + Waist-to-Hip Ratio (research-backed proxies)
- **Muscle Loss Alerts** — Flags if you're losing more muscle than fat
- **Workout Timer** — Custom bodyweight exercise routines with work/rest intervals
- **Progress Charts** — Weight, body fat, muscle mass, waist trends
- **Goal Tracking** — Visual progress bar toward target weight
- **Photo Storage** — Screenshots saved with each check-in for reference
- **Data Export** — JSON export of all data
- **PWA** — Install to home screen, works offline

## Setup

1. Host files on GitHub Pages or any static hosting
2. Open in browser → Add to Home Screen
3. Go to Settings → Set your height, age, goal weight

## Files

```
index.html      — The full app (single file)
manifest.json   — PWA manifest
sw.js           — Service worker for offline support
icon-192.png    — App icon (192x192)
icon-512.png    — App icon (512x512)
```

## Tech

- Single HTML file, no build tools
- Claude API for screenshot reading (works in Claude.ai artifacts)
- localStorage for data persistence
- Vanilla JS, no frameworks
