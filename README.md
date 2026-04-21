# mpv-modernP
A highly optimized, battery-friendly OSC and File Browser for MPV player. Built for zero background processing and seamless binging.

# ModernP

A minimal, resource-efficient On-Screen Controller (OSC) and custom UI for the MPV media player. 

Forked from [maoiscat/mpv-osc-modern](https://github.com/maoiscat/mpv-osc-modern) and [cyl0/ModernX](https://github.com/cyl0/ModernX), this version is optimized for zero background processing and maximum battery efficiency.

![Main Player Preview](preview1.mp4)

## Features

### File Browser Overlay
Navigate local directories directly within MPV. Supports Grid and List views, sorting (A-Z, Date), and an instant typing-based search.

![File Browser Screenshot](link-to-your-browser-screenshot)

### Playlist Overlay
View and manage your current queue with visual progress tracking. Includes green checkmarks (`✓`) for completed files and watched timestamps.

![Playlist Screenshot](link-to-your-playlist-screenshot)

### Audio & Subtitle Overlays
Clean, native menus to quickly cycle through or select specific audio and subtitle tracks without cluttering the interface.

![Audio-Sub Screenshot](link-to-your-audio-sub-screenshot)

### Chapters Overlay
Navigate through video chapters with a dedicated menu showing precise timestamps for each segment.

![Chapters Screenshot](link-to-your-chapters-screenshot)

## Installation

1. Disable the default OSC. Add the following to your `mpv.conf`:
   ```ini
   osc=no
   ```
2. Place `modernP.lua` into your MPV scripts directory:
   * **Windows:** `%APPDATA%\mpv\scripts\`
   * **Linux/macOS:** `~/.config/mpv/scripts/`
3. Delete any existing `osc.conf` in your `script-opts` folder to avoid configuration conflicts.

## Key Bindings

| Key | Action |
| --- | --- |
| **`O`** | Toggle File Browser |
| **`TAB`** | Toggle Playlist |
| **`C`** | Toggle Chapters Menu |
| **`A`** / `Shift+A` | Cycle / Toggle Audio Tracks Menu |
| **`S`** / `Shift+S` | Cycle / Toggle Subtitle Tracks Menu |
| **`Arrows` / `Scroll`** | Navigate through menus and grids |
| **`ENTER` / `Click`** | Play selected file or open folder |
| **`Typing`** *(in Browser)* | Instantly search/filter files and folders |

## Credits
* [maoiscat](https://github.com/maoiscat/mpv-osc-modern) - Original creator of *mpv-osc-modern*.
* [cyl0](https://github.com/cyl0/ModernX) - Creator of the *ModernX* fork.
* **pspok** - Creator of *ModernP* (Refactoring, Overlay integration, and battery optimization).
