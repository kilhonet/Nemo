# Nemo

**Free sticky notes for your Windows desktop. Notes are saved on this PC right away, and once you sign in you can use the same notes on several PCs and on the web.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%207%20%2F%208%20%2F%2010%20%2F%2011-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/nemo?lang=en)

![Nemo screenshot](images/nemo-en.png)

## Overview

Nemo lets you jot down a thought on a note and stick it to your desktop. Each note has a title and a body, and it saves itself when you stop typing. You can give every note its own color and pin it above other windows, and its position, size and pin come back exactly as they were the next time you start Nemo.

Notes are **saved on this PC first**, so you can use Nemo without signing in and even without an internet connection. Sign in with a Kilho.net account and your notes sync with the server, so you can see and edit the same notes in Nemo on your other PCs and in [Web Memo](https://webmemo.kilho.net).

## Features

- **Desktop notes** — note windows don't take up room on the taskbar or in Alt+Tab, and they stay on the desktop when you close the list window.
- **Auto-save** — a note is saved 3 seconds after you stop typing, or when you click somewhere else. There is no Save button.
- **Remembers where you left it** — position, size, pin and which notes were open are remembered and restored on the next launch.
- **6 colors** — Default · Yellow · Green · Blue · Purple · Pink. The list shows each row in its note's color, so you can tell them apart at a glance.
- **Always on top** — a pinned note never gets hidden behind other windows.
- **Note search** — the magnifier in the list window searches titles and bodies.
- **New note shortcut** — press **Ctrl+Shift+N** from any program to open a new note. You can change the key.
- **Works without a server** — signing in is optional. When you sign out, the notes on this PC stay.
- **Sync across PCs and the web** — once signed in, Nemo syncs with the server 2 seconds after saving, every 10 minutes, or when you click **Sync now**. If the same note was edited in two places, neither edit is thrown away: both are kept, one as a **conflict copy**.
- **Secure sign-in through your browser** — you never type your password into Nemo. You sign in with your Kilho.net account in the browser you already use (OAuth 2.0 + PKCE).
- **Emoji** — put emoji in titles and bodies.
- **22 languages** — follows the Windows display language, or pick one yourself in Settings.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/nemo?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/nemo?lang=en&nosetup) |

A first-time install of the installer version turns on **Run at startup**. For the portable version, unzip it and run `Nemo.exe`. The portable version keeps your notes in the same folder as the program, so moving the folder moves your notes with it.

## Usage

### Getting started

1. Start Nemo. The list window opens and a Nemo icon appears in the notification area (tray).
2. Right-click an empty spot in the list or the tray icon and choose **New note**. (You can also press **Ctrl+Shift+N** anywhere.)
3. A new note opens with the title field ready. Type a title and press **Enter** to move to the body.
4. Type the body. When you stop typing, the note is saved 3 seconds later and appears in the list.
5. Leave the note anywhere on your desktop. Drag the title bar to move it and drag an edge to resize it.
6. When you're done, click the note's **✕**. It is saved and closed. To open it again, double-click it in the list.

### Screen layout

**List window**

| Element | Description |
|---|---|
| Magnifier (caption) | Search notes. Looks in titles and bodies; **ESC** closes it |
| Gear (caption) | Settings |
| ✕ (caption) | Hides the list window to the tray. Nemo keeps running |
| Note list | Shown in the order the notes were created, each row in its note's color. Double-click to open the note |
| Status bar, left | **Notes: n** |
| Status bar, right — cloud icon | Server connection. Hover to see **Saved on this PC only** · **Connected to server (account)** · **Last sync**; click to open the **Server** page of Settings |

**Note window**

| Element | Description |
|---|---|
| Title bar | Drag to move the note. Click the title twice or double-click it to rename. Right-click for the note menu |
| Pin | Turns **Always on top** on or off. Off is shown as a pin with a slash |
| ✕ | Save and close |
| Body | The note's text. A scroll bar appears when the mouse is over it |
| Edges | Drag to resize |

**Right-click menu**

| Menu | Where | What it does |
|---|---|---|
| **New note** | List · Tray | Opens a blank note |
| **List** | Tray (when the list window is hidden) | Shows the list window again |
| **Edit** | List (on a note) · Note title bar | Opens the note / renames it |
| **Delete** | List (on a note) · Note title bar | Asks once, then deletes |
| **Color ▸** | List (on a note) · Note title bar | Pick one of the 6 colors. Saved right away |
| **Settings** | List · Tray | Opens Settings |
| **Kilho.net** | List · Tray | Nemo's introduction page |
| **Quit** | List · Tray | Asks once, then closes Nemo. Open notes come back on the next launch |

### Tips for common situations

**When an idea hits you in the middle of work**
Even while you're in another program, press **Ctrl+Shift+N** and a new note pops up in front. Type a title, press Enter, type the body and leave it — it saves itself.

**When you want a note always in sight**
Click the note's pin to turn on **Always on top**; other windows won't cover it. Click again to turn it off. The pin is restored on the next launch, too.

**When your notes are buried behind other windows**
Left-click the Nemo tray icon to bring every open note to the front. The list window stays where it is. If you need the list window, right-click the tray icon and choose **List**.

**When you want to sort notes by kind**
Pick a color scheme — yellow for to-dos, blue for work, and so on. Right-click a note's title bar or a note in the list → **Color ▸**, and both the note and its row in the list change color right away.

**When you have too many notes to find one**
Click the magnifier in the list window's caption and type what you're looking for. Only notes with that text in the title or body remain. Press **ESC** to close the search and see the whole list again.

**When you only want to rename a note**
Click the note's title, then click it once more a moment later (just like renaming a file in File Explorer), double-click it, or right-click the title bar → **Edit**. **Enter** confirms, **Esc** brings back the old title. Clicking somewhere else also keeps what you typed.

**When you want the list out of the way but the notes kept**
Click **✕** on the list window; it goes to the tray and your notes stay on the desktop. To close Nemo completely, choose **Quit** from the tray menu.

**Notes come back right where you left them**
Even if you shut down Windows or quit Nemo with notes still open, they reappear in the same place and size the next time you start Nemo. If a note would land off screen because your monitor setup changed, it is moved back onto the screen.

**When you want your notes every time the PC starts**
Turn on **Run at startup** in Settings → **General** (it is already on with the installer). When Windows starts, Nemo starts quietly in the tray without the list window, and only the notes you left open appear on the desktop.

**When you want the same notes at work and at home**
On both PCs, click **Sign in** in Settings → **Server**. Your browser opens; sign in with your Kilho.net account, and when the "Signed in" page appears, close it and return to Nemo. From then on, notes sync by themselves 2 seconds after saving and every 10 minutes. To sync right now, click **Sync now**.

**When you're away from your PC**
Sign in to [Web Memo](https://webmemo.kilho.net) with the account you use in Nemo to view and edit the same notes. Changes you make on the web arrive in Nemo's notes at the next sync.

**When the same note was edited on two PCs**
Nothing is overwritten. One version stays as the original note and the other becomes a new note with **(conflict copy)** at the end of its title. Compare them, merge what you need into one, and delete the other.

**When you already have notes from before signing in**
When you sign in, the notes on this PC go up to that account and the notes on the server come down to this PC, all in one list. If the PC was used with a different account before, Nemo first asks "You signed in with a different account. Merge the notes on this PC into this account?" — choose **No** and Nemo doesn't sign in.

**When you want to stop syncing and keep notes on this PC only**
Click **Sign out** in Settings → **Server**. The notes on this PC stay, and the status bar changes to **Saved on this PC only**. Notes on the server and on your other PCs are left untouched.

**When you have no internet**
Notes are always saved on this PC first, so just keep using Nemo as usual. When you're back online, they go up to the server at the next sync.

**When you want a different new-note shortcut**
Click the **Shortcut (new note)** box in Settings → **General**; it changes to "Press a key". Press the combination you want (for example Ctrl+Alt+M) and it takes effect right away. If another program already uses that key, Nemo tells you, so pick another one.

**When you want to carry Nemo on a USB stick**
Unzip the portable version onto the USB stick and run it there. Notes are saved in the same folder, so the same notes open on every PC you plug it into.

**When you uninstall and reinstall Nemo**
Uninstalling the installer version does not delete your notes. Install again and your notes are right there.

**When you shut down Windows**
Nemo never holds up shutdown. It saves the notes you were writing and closes along with Windows.

**When you start Nemo again and see no window**
Only one copy of Nemo runs at a time. If you start it while it's already running, the list window comes out of the tray to the front.

## Configuration

Open it from the gear in the list window or **Settings** in the right-click menu. Changes apply immediately; there is no OK button.

| Page | Item | Default |
|---|---|---|
| General | Run at startup | On for the installer, off for the portable version |
| General | Shortcut (new note) | Ctrl+Shift+N |
| General | Language | System (Windows display language) |
| Server | Account — Sign in / Sign out | Not signed in |
| Server | Sync — last sync time, Sync now | Shown only while signed in |
| About | Version · Author · Website · Licenses | — |

With **System**, the language follows the Windows display language; pick one from the list and it switches on the spot. Arabic is displayed right to left.

## Requirements

- Windows 7 · 8 · 8.1 · 10 · 11 (32-bit · 64-bit)
- No extra runtime needed.
- An internet connection and a Kilho.net account are needed only for server sync.

## Updates

Nemo does **not** update itself. When it starts, it checks for a new version and shows a notice; click **Yes** to open the download page, and the program closes. New versions are released manually after internal testing and announced on the [Nemo page](https://kilho.net/nemo). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

Nemo is **freeware**. You can use it free of charge anywhere — at the office, at home, in government offices or at school — and redistribute it freely.

## Links

- Website: <https://kilho.net/nemo>
- Nemo homepage: <https://nemo.kilho.net>
- Web Memo: <https://webmemo.kilho.net>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
