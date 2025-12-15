# Snap Permission Manager

Two small Bash tools to manage **Snap interface connections** in a user-friendly way.
The scripts allow you to view, connect, and disconnect Snap interfaces without using the terminal directly.

---

## Scripts

### 1. `snap-permissions`
Graphical version using **YAD** (GTK).

**Features**
- GUI-based Snap selection
- Interface status (ON / OFF)
- Connect & disconnect interfaces
- Uses `pkexec` (preferred) or `sudo` fallback
- Filters base snaps (`core`, `bare`, `snapd`)

**Requirements**
- snap
- yad
- pkexec (optional, recommended)

---

### 2. `snap-permissions-cli`
Terminal UI version using **dialog** (black & white theme).

**Features**
- Text-based menu interface
- High-contrast B&W layout
- Interface status display
- Connect & disconnect via `sudo`
- Filters base snaps (`core`, `bare`, `snapd`)

**Requirements**
- snap
- dialog
- sudo

---

## Installation

Download Files 

Install yad and dialog on your system


set execute permission with :
```bash
chmod +x

