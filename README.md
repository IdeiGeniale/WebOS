# 🌐 Web OS Simulator

**Web OS Simulator** is a fully interactive, browser-based operating system simulation built entirely with **HTML, CSS, and JavaScript** — no external frameworks required.  
It recreates the experience of a desktop operating system directly inside your browser, with real, functional apps and persistent user data.

---

## ✨ Features

### 🖥️ System
- **User Login System** — Three accounts (`admin`, `user`, `guest`) with saved sessions via `localStorage`.  
- **Customizable Desktop** — Change background colors, drag windows, and arrange icons freely.  
- **Taskbar & Start Menu** — Just like Windows, with running app indicators and a working clock.  
- **Persistent Settings** — All user preferences, notes, files, and app data are saved locally.

---

## 🧩 Included Applications

| App | Description |
|-----|--------------|
| 📧 **Email Client** | Real email sending using [EmailJS API](https://www.emailjs.com/). Compose, send, and view sent mail. |
| 🌐 **Browser** | Built-in web browser with address bar, navigation, refresh, and iframe sandbox. |
| 📝 **Notepad** | Write and save notes directly in localStorage. |
| ✏️ **File Editor** | Create, edit, and delete local text files. |
| 🗂️ **File Manager** | Manage files stored locally via `localStorage`. |
| 🧮 **Calculator** | Embedded scientific calculator using Desmos. |
| >_ **Terminal** | Command-line interface with commands like `/openapp`, `/setbg`, `/help`, and more. |
| ⚙️ **Settings** | Adjust volume, test sound, and customize desktop background color. |
| 🎵 **Music Player** | Select and play any audio file from your device. |
| 🖼️ **Media Viewer** | View images or play videos (PNG, JPG, MP4, AVI supported). |
| 🎮 **Games** | Play classic browser games like Flappy Bird, Solitaire, Tetris, and Breakout. |
| ✅ **To-Do List** | Add, check, and delete personal tasks — saved automatically. |
| 📅 **Calendar** | Interactive monthly calendar with event creation and deletion. |
| 🎨 **Drawing App** | Full-featured canvas for drawing, coloring, saving, and reloading artwork. |

---

## 🔐 Login Credentials

| User | Password | Description |
|------|-----------|-------------|
| `user` | `letmein` | Standard user account |
| `guest` | `guest` | Guest account with limited customization |

---

## ⚙️ Technologies Used

- **HTML5** — Structure and app containers  
- **CSS3** — Window styling, layout, and desktop design  
- **JavaScript (Vanilla)** — Logic for multitasking, localStorage persistence, and app handling  
- **EmailJS API** — Sends real emails through Gmail or other providers  
- **Desmos Embed** — Scientific calculator integration

---

## 💾 Data Persistence

- User data (login session, background color, notes, drawings, files, events, etc.) is stored in `localStorage`.
- Clearing browser storage resets the OS to default.

---

## 🧠 Terminal Commands

| Command | Description |
|----------|-------------|
| `/openapp [id]` | Open an app by ID (e.g., `/openapp notepad`) |
| `/closeapp [id]` | Close an open app |
| `/setbg [color]` | Change desktop background color |
| `/resetbg` | Reset background to default |
| `/logout` | Log out current user |
| `/help` | Display all available commands |

---

## 🚀 Usage

1. Open the file `webos-latest-2025-11-03.html` in your browser.  
2. Log in using one of the provided credentials.  
3. Explore the desktop environment and launch apps from icons or the **Start** menu.  
4. All progress is auto-saved!

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/<your-repo>.git

# Open the project folder
cd <your-repo>

# Run directly in your browser
start webos-latest-2025-11-03.html

