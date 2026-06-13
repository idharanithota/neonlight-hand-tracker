# ✦ Neon Hand Tracker ✦

A real-time hand-tracking visualizer that draws glowing neon skeleton lines over your hands using your webcam — built with **MediaPipe Hands**.

## 🔗 Live Demo

Try it here: https://idharanithota.github.io/neonlight-hand-tracker/

## Features

- 🖐️ Tracks up to **2 hands** simultaneously
- 🌈 Neon glow skeleton with multi-layer lighting effect
- ✨ Connects matching fingertips/joints **between both hands** for a glowing "web" effect
- 📊 Live overlay showing **FPS**, **gesture detection** (Open Hand, Fist, Peace, Pointing, Thumbs Up), and **hand spread %**
- ⚡ Runs entirely in the browser — no install, no backend

## How to Use

1. Open `index.html` in **Google Chrome** (or any modern browser)
2. Click **Enable Camera**
3. Allow camera permissions when prompted
4. Show one or both hands to the camera

## Tech Stack

- [MediaPipe Hands](https://developers.google.com/mediapipe) — hand landmark detection
- HTML5 Canvas — rendering the neon skeleton overlay
- Vanilla JavaScript — no frameworks, no build step
