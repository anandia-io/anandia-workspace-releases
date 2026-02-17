# Anandia Workspace

![Anandia Workspace - Tactile Productivity](hero.png)

A tactile workspace for Projects, Tasks, Notes, and Habits.

## Download

| Platform | Download | Status |
|----------|----------|--------|
| Windows (x64) | [Download Installer](../../releases/latest) | Available |
| macOS (Apple Silicon) | [Download .dmg](../../releases/latest) | Available |
| Linux (deb/AppImage) | [Download](../../releases/latest) | Available |

> **Windows:** Builds are currently unsigned. You may see a SmartScreen warning — click "More info" then "Run anyway" to install. Code signing is coming soon.
>
> **macOS:** Builds are not yet notarized. After installing, run the following command to remove the quarantine flag:
> ```
> xattr -d com.apple.quarantine /Applications/Anandia\ Workspace.app
> ```
> Code signing and notarization are coming soon.
>
> **Linux:** The `.deb` package is the recommended format. AppImage is also available.

## Features

### Spaces

Organize your work into distinct Spaces, each with its own set of views. Create and customize Spaces with dedicated SpaceCards and an edit dialog. Navigate between Spaces from the sidebar.

Each Space contains multiple zones you navigate with **WASD keyboard chords**:

- **Default** — your home zone
- **Board** — Kanban-style drag-and-drop task board with column headers
- **Tasks** — detailed task list with inline editing
- **Notes** — browse and edit notes with a card layout and rich text editor
- **Projects** — view and manage projects
- **Habits** — track and complete habits with different completion actions
- **Kalendar** — full month-view calendar with drag-and-drop task scheduling
- **Media** — media gallery for images and files

### Navigation

- **WASD chords** — press key combinations to jump between zones (e.g. `DD` to move two zones right)
- **Radial menu** — right-click to open a wheel menu for quick actions and zone navigation
- **Slice** — Archive items from the canvas with a satisfying swipe gesture. Slice to complete a habit.
- **Quick Notes** — create notes instantly from the radial menu
- **Visor Frame** — perspective viewport effect with zone-aware HUD labels

### Item Types

- **Tasks** — status tracking, priorities, due dates, and recurring task support
- **Habits** — daily tracking with streaks, targets, and reminders
- **Notes** — rich text editing with slash commands, images, and callouts
- **Projects** — progress tracking, timelines, and status workflows

### Local-First Architecture

- All data stored locally in SQLite — no account required
- Works completely offline
- Auto-save as you work — no save button needed

### Auto-Updates

- Automatic update checking and installation

## Installation

| Platform | Download | Notes |
|----------|----------|-------|
| Windows | [.exe installer](../../releases/latest) | Unsigned — SmartScreen warning expected |
| macOS (Apple Silicon) | [.dmg](../../releases/latest) | Run `xattr` command after install (see above) |
| Linux | [.deb (recommended)](../../releases/latest) | AppImage also available |

### Windows

1. Download the `.exe` installer from the latest release
2. Run the installer and follow the prompts
3. Launch Anandia Workspace from the Start menu

### macOS

1. Download the `.dmg` from the latest release
2. Drag Anandia Workspace to your Applications folder
3. Open a terminal and run:
   ```
   xattr -d com.apple.quarantine /Applications/Anandia\ Workspace.app
   ```
4. Launch Anandia Workspace from Applications

### Linux

1. Download the `.deb` package (recommended) or `.AppImage` from the latest release
2. Install the `.deb` with `sudo dpkg -i anandia-workspace_*.deb`
3. Launch from your application menu

## System Requirements

- **Windows**: Windows 10 or later (x64)
- **macOS**: macOS 11+ (Apple Silicon)
- **Linux**: Ubuntu 20.04+ or equivalent

## Links

- [Website](https://workspace.anandia.io)
- [Report Issues](https://github.com/anandia-io/anandia-workspace-releases/issues)
- [Robot](https://robot.co/) Slice and node inspiration from ([GitHub](https://github.com/dashrobotco/robot-components))

## Change Log

[See CHANGELOG.md](CHANGELOG.md)

## Legal

- [License Agreement](LICENSE.md)
- [Terms of Service](TERMS.md)
- [Privacy Policy](PRIVACY.md)



## License

Anandia Workspace is proprietary software. Free for personal use and small businesses (fewer than 10 employees). See the [License Agreement](LICENSE.md) for full terms.

---

Copyright 2026 Tony Alfredsson AB. All rights reserved.
