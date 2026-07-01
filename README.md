# Nexura OS

**A futuristic, fully interactive browser-based operating system that blends the best of Windows 11, macOS, Android, ChromeOS, and modern Linux distributions – all in a single HTML file.**

---

## ✨ Overview

Nexura OS is a proof‑of‑concept operating system that runs entirely inside your web browser. It was built to push the boundaries of what a single HTML file can do. From a realistic boot animation to a fully functional desktop with draggable windows, a taskbar, start menu, and a suite of built‑in applications, Nexura OS simulates a modern OS experience without any frameworks, libraries, or build tools.

Every piece of the interface – the glass‑morphism windows, the blur effects, the animations – was crafted using plain HTML, CSS, and JavaScript. The entire project is contained in a single `.html` file that can be opened directly in any modern browser.

---

## 🚀 Features

### 🖥️ Core Operating System
- **Boot Screen** – Animated logo, progress bar, system checks, and boot messages.
- **Lock Screen** – PIN‑based authentication (default PIN `1234`), live clock, and date.
- **Desktop** – Icons for built‑in apps and installed store apps. Resizable, draggable windows.
- **Taskbar** – Centered running apps, start button, quick settings, clock, and system tray.
- **Start Menu** – Search bar, pinned apps grid, and power options (lock, restart, shutdown).
- **Window Management** – Minimize, maximize, close, drag, and resize. Multiple windows simultaneously.

### 📦 Built‑in Applications
- **Aura Browser** – Integrated **Google Custom Search** (CSE) right inside a window.
- **Files** – Sidebar quick access and a grid of sample files.
- **Nexura Terminal** – Fully interactive with commands like `help`, `neofetch`, `open`, `install`, `uninstall`, `roll`, `flip`, `funfact`, `joke`, etc.
- **Calculator** – Full arithmetic with memory.
- **Settings** – Tabbed panels (Appearance, Desktop, Taskbar, Lock Screen, Background, Accounts, History) with live preview of changes.
- **Notes** – Simple notepad.
- **Music** – Spotify embed (blocked by CSP in some environments, falls back to external link).
- **Nexura Paint** – Drawing canvas with brush, eraser, rectangle, clear, and save.
- **Code Editor** – Write and run JavaScript code.
- **Weather** – Static weather display.
- **App Store** – Dozens of apps, each with an icon, a name, a clickable “Open ↗” link (opens in new tab), and an Install/Uninstall button. Pre‑loaded with Google apps, Workspace tools, AI chat services, creative suites, modding tools, and much more.
- **Game Launcher** – Playable Snake and Pong games.
-And more 
### 🎨 Personalization
- Adjustable **blur**, **transparency**, **border radius**, **shadow intensity**, **icon size**, **taskbar transparency**, and **auto‑hide** – all changes apply instantly.
- **Background customization** – choose between gradient, particles, solid colour, or upload an image/URL.
- **Account PIN** – change your lock screen PIN directly from Settings.

### 🕹️ Games
- **Snake** – classic with score and restart.
- **Pong** – vs. AI with score and restart.

### 📜 Activity History
Every login attempt, app open, install/uninstall is logged with a timestamp and can be viewed in Settings → History.

---

## 🌐 Demo

You can try Nexura OS right now by opening the `Nexura OS.html` file in your browser, or by hosting it on any static server (GitHub Pages, Netlify, etc.).

https://hcodx.com/vs-editor?project=p_mr1u1k2o_3z0iv1

---

## 🛠️ Getting Started

1. **Clone the repository** or download the `Nexura OS.html` file.
   ```bash
   git clone https://github.com/Kiik913/Nexura-OS.git
   cd Nexura-OS
   ```

2. **Open the file** in your favourite browser:
   - Double‑click `Nexura OS.html`, or
   - Drag and drop it into a browser window.

3. **Unlock** the OS by entering the default PIN: **`1234`**

No server, no build step, no dependencies – just a browser.

---

## 📖 Usage

- **Start Menu** – Click the 🟣 button on the taskbar, or press `Ctrl+E` to open Files, `Escape` to close menus.
- **Install apps** – Open the **App Store**, browse or search, and click **Install**. Installed apps appear on the desktop.
- **Customize** – Go to **Settings** → Appearance, move the sliders, and see the OS change in real time.
- **Change PIN** – Settings → Accounts.
- **Play games** – Open the **Games** launcher.

---

## 🧑‍💻 Technical Details

- **No frameworks** – Zero dependencies. Pure HTML, CSS, and vanilla JavaScript.
- **Single file** – Everything is embedded (inline styles, inline script). No external resources except the Google CSE script.
- **Local Storage** – Your installed apps, settings, history, and PIN are saved in `localStorage` so they persist across sessions (same browser).
- **Window Manager** – Full implementation with z‑index handling, dragging, resizing from all eight edges, and maximize/restore.
- **App Store** – Dynamically generated cards with unique icons (deduplication pool of 200+ emojis).

---

## 🎨 Customization

You can easily modify the App Store to add your own links by editing the `apps` array inside the `setupStoreApp` function. Each entry follows this format:
```javascript
{id:'unique_id', name:'Display Name', icon:'🖥️', url:'https://example.com'}
```

---

## 📸 Screenshots

| Boot | Lock Screen | Desktop |
|------|-------------|---------|
| ![Boot](https://via.placeholder.com/200?text=Boot) | ![Lock](https://via.placeholder.com/200?text=Lock) | ![Desktop](https://via.placeholder.com/200?text=Desktop) |

| App Store | Terminal | Paint |
|-----------|----------|-------|
| ![Store](https://via.placeholder.com/200?text=Store) | ![Terminal](https://via.placeholder.com/200?text=Terminal) | ![Paint](https://via.placeholder.com/200?text=Paint) |

---

## 🤝 Credits

- **Developed by** – Aura Lab Studios / Kavyant Kumar
- **GitHub** – [@Kiik913](https://github.com/Kiik913)
- **Inspiration** – Windows 11, macOS, Android, ChromeOS, and countless late‑night coding sessions.

---

## 📜 License

This project is open‑source and available under the MIT License. Feel free to fork, modify, and share!

---

## ⭐ Star the Repo

If you like this project, please give it a ⭐ on GitHub – it really helps!
