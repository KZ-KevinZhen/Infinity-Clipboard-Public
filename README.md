# Infinity Clipboard

A powerful clipboard manager built with Electron and Next.js that allows you to store, organize, and manage your clipboard history.

## Team
- **Kevin Zhen** – Founder &  Leader Developer
- **Hensen Hy** – Business Relations / Marketing & Development

## Features

- 📋 Infinite clipboard history
- 🖼️ Support for text, code, links, and images
- 📁 Organize items in folders
- ⭐ Favorite important items
- 🔍 Search through your clipboard history
- 🎨 Modern and intuitive interface
- 🔄 Export and share clipboard items
- 🔒 Local database storage for privacy
- ⌨️ Custom Global shortcut to quickly access clipboard history default (Alt+/)
- 🚀 Auto-start on system boot

## Installation

### Option 1: Install using the Setup Wizard (Recommended)
1. Download the latest `Infinity Clipboard Setup.exe` from the [Releases](https://github.com/KZ-KevinZhen/infinity-clipboard-public/releases) page
2. Run the installer
3. Follow the installation wizard
4. Launch Infinity Clipboard from your Start menu

[Watch the YouTube Video](https://www.youtube.com/watch?v=OsXfHiml994)


[![Watch the video](https://img.youtube.com/vi/OsXfHiml994/maxresdefault.jpg)](https://www.youtube.com/watch?v=OsXfHiml994)


## Usage

- Use the custom global shortcut default (Alt+/) to open the clipboard manager
- Click on any item to copy it back to your clipboard
- Right-click items for additional options (favorite, delete, export, etc.)
- Use the search bar to find specific items
- Create folders to organize your clipboard items
- Access settings through the system tray icon

### Settings
- Customize the global shortcut
- Set maximum database size
- Enable/disable auto-start
- Configure backup options
- Manage excluded applications

## Development

The project uses:
- Electron for the desktop application
- Next.js for the user interface
- SQLite for local database storage
- Tailwind CSS for styling

### Project Structure
```
infinity-clipboard/
├── electron/         # Electron main process code
├── src/             # Next.js application code
├── public/          # Static assets
└── out/            # Production build output
```

