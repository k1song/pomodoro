# 🍅 Pomo — Aesthetic Pomodoro Timer

A beautiful, distraction-free Pomodoro timer. Start focusing in one click — no installation needed.

🌐 **Live**: [bettermemap.com](https://bettermemap.com)

---

## Features

### ⏱ Timer
- Focus / Break mode tab switching
- Edit time directly inside the timer ring (▲▼ buttons + direct input)
- Entering 60+ in MIN auto-converts to HR/MIN format
- 5-second countdown animation before each session
- Pause / Stop control while running

### ⏰ Overtime
- When time's up, overtime counter starts automatically (+00:01, +00:02...)
- Overtime is included in today's total focus time
- **Continue**: dismiss alarm and keep focusing with overtime running
- **Stop**: end session and move to the next

### ✅ Tasks
- Add tasks with the input field (Add button or Enter) — up to 10
- Click a task to select it → automatically marked done when focus session ends
- ✎ inline edit, ✓ or Enter to save
- ⠿ drag handle to reorder
- × delete with inline confirmation
- ○ manually toggle done/undone
- Data persists across page refreshes (localStorage)

### 🔔 Alarm
- **Alarm Notify**: browser pop-up notification on/off at session end
- **Alarm Sound**: 1-minute alarm sound on/off at session end
- **5 sound types**: Gentle Bell · Tibetan Bell · Harp Arpeggio · Guitar Harmonic · Aurora

### 🎨 Viewer & Sound
- **8 themes**: Lofi · Sunset · Forest · Galaxy · Yellow · Vivid · Rainbow · Dawn
- **Text size**: 5-step adjustment with +/− buttons
- **Background sound**: Rain · Café · Fire · Waves · Wind (plays independently of timer state)
- **Mute**: 🔊 button or `M` key to instantly mute/unmute
- **Fullscreen** mode
- **Hide Numbers**: auto-hides timer display while running, reappears on pause

### 📊 Stats
- Today's completed sessions 🍅
- Today's total focus time ⏱ (overtime included)
- Auto-resets at midnight

### 🌐 Internationalization
- 11 languages: English · 한국어 · 日本語 · 中文 · हिन्दी · Español · Français · Português · Bahasa Indonesia · Deutsch · Tiếng Việt
- Language selector in Settings (dropdown)
- Auto-detects browser language on first visit
- 💾 All settings saved automatically (localStorage)

---

## Keyboard Shortcuts

| Key | Action |
|---|---|
| `Space` | Start / Pause |
| `F` | Toggle fullscreen |
| `H` | Toggle hide numbers |
| `M` | Mute / Unmute background sound |

---

## Getting Started

Single `index.html` file — no build step, no dependencies.

```bash
# Open locally
open index.html

# Or serve with a simple server
npx serve .
```

## Deploy

Deploy instantly to Vercel, Netlify, GitHub Pages, or Cloudflare Pages.

## Tech Stack

- Vanilla HTML / CSS / JS (zero frameworks)
- Web Audio API (5 alarm sounds + 5 background sounds, procedurally generated)
- Web Notifications API
- Google Fonts (Outfit, Noto Sans KR/SC)

## License

MIT
