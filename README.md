# pomodoro-app
Pomodoro App for focus work management
# Pomodoro Timer

A clean, no-frills Pomodoro timer built as a single HTML file. No installation, no sign-up, no dependencies — open it in a browser and start focusing.

Live at: `https://darshakp1.github.io/pomodoro-app`

---

## What is the Pomodoro Technique?

The Pomodoro Technique is a time management method developed by Francesco Cirillo. The idea is simple: work in focused intervals (typically 25 minutes), separated by short breaks. After a set number of focus sessions, you take a longer break. This rhythm helps sustain concentration, reduce mental fatigue, and build a sense of daily accomplishment.

---

## Features

- **Focus, short break, and long break modes** — color-coded tabs make it immediately clear which mode is active
- **Preset duration pills** — choose your focus length (25–45 min), short break (5–13 min), and long break (15–30 min) with one tap; no sliders to fiddle with
- **Configurable session cycles** — set 3, 4, or 5 focus sessions before a long break kicks in
- **Progress tracker** — numbered bars fill in as you complete each session in a cycle
- **Auto-start toggle** — chain sessions automatically, or start each one manually
- **Encouragement messages** — a rotating message appears at the start of each session to keep you grounded
- **Chime notification** — a soft three-note sound plays when a session ends (can be turned off)
- **Five theme accents** — teal, coral, purple, blue, and amber
- **Session history** — a summary tab shows today's count, this week's total, all-time sessions, and total focused minutes
- **30-day calendar heatmap** — see your focus patterns at a glance, with intensity shading by session count
- **Persistent storage** — all history and preferences are saved automatically in your browser via `localStorage`; nothing is sent to a server
- **Dark mode** — automatically follows your system preference
- **No install required** — one HTML file, works in any modern browser

---

## How to Use

### Starting a session

1. Open the app — the timer starts in **Focus** mode at 25 minutes by default
2. Press **Start** to begin the countdown
3. Press **Pause** to pause mid-session; press **Resume** to continue
4. When the session ends, a chime plays and the next mode begins automatically (if auto-start is on) or waits for you to press Start

### Switching modes manually

Tap any of the three mode tabs at the top of the timer — **Focus**, **Short break**, or **Long break** — to switch at any time. Switching mid-session stops the current timer.

### Resetting a session

Press the **reset (↺) button** on the left of the controls. If the timer has started, a confirmation dialog will appear to prevent accidental resets.

### Skipping a session

Press the **skip (⏭) button** on the right of the controls to advance to the next session in the cycle without waiting for the timer to finish.

### Reading the progress tracker

The **Progress** bar beneath the controls shows numbered bars — one per focus session in your current cycle. Bars fill as sessions complete and reset after a long break.

---

## Settings

Open the **Settings** tab to customize the app.

| Setting | Options | Default |
|---|---|---|
| Focus duration | 25, 30, 35, 40, 45 min | 25 min |
| Short break | 5, 7, 9, 11, 13 min | 5 min |
| Long break | 15, 20, 25, 30 min | 15 min |
| Sessions before long break | 3, 4, 5 | 4 |
| Auto-start next session | On / Off | Off |
| Sound on session end | On / Off | On |
| Theme accent | Teal, Coral, Purple, Blue, Amber | Teal |

All settings are saved automatically and persist across browser sessions.

---

## Summary Tab

The **Summary** tab shows:

- Sessions completed today
- Sessions completed this week (rolling 7 days)
- All-time session count
- Total focused minutes
- Your current session goal and focus length
- A **monthly calendar heatmap** — each day shades darker based on how many sessions you completed; use the arrow buttons to navigate between months

History is stored locally in your browser. You can clear it at any time via **Settings → Clear all history**.

---

## Privacy

This app stores data only in your browser's `localStorage`. No data is collected, transmitted, or shared. Nothing leaves your device.

---

## Deployment

This app is a single `index.html` file. To host it yourself:

1. Fork or download this repository
2. Go to **Settings → Pages** in your GitHub repo
3. Set the source to **Branch: main / folder: / (root)**
4. Save — your app will be live at `https://yourusername.github.io/your-repo-name` within a minute

No build step, no dependencies, no configuration required.

---

## Browser Support

Works in all modern browsers: Chrome, Safari, Firefox, and Edge. Optimized for both desktop and mobile viewports.

---

## License

MIT — free to use, modify, and distribute.
