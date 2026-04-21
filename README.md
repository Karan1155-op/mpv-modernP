# mpv-modernP
A highly optimized, battery-friendly OSC and File Browser for MPV player. Built for zero background processing and seamless binging.

# ModernP

A modern OSC UI replacement for MPV, featuring a highly optimized built-in File Browser. Forked from [cyl0/ModernX](https://github.com/cyl0/ModernX) and completely refactored for zero background processing and maximum battery efficiency.

![ModernP](link-to-your-video-or-screenshot)

## Features
- **Smart File Browser:** Toggle between Grid and List views with Universal Search and sorting.
- **Battery Optimized:** Zero background processing, no forced FFmpeg rendering.
- **Bulletproof Resume:** Native hash-matching ensures perfect resume times across all navigation methods.
- **Visual Progress Tracking:** Automatically tracks watched episodes with `✓` and precise timestamps.
- **Clean Overlays:** Intuitive native menus for Playlists, Audio, Subtitles, and Chapters.

## Installation
1. Disable the default OSC by adding `osc=no` in your `mpv.conf`.
2. Drop `modernP.lua` into your mpv `scripts` directory:
   * **Windows:** `%APPDATA%\mpv\scripts\`
   * **Linux/macOS:** `~/.config/mpv/scripts/`
3. Delete any existing `osc.conf` in your `script-opts` folder to prevent clashes.
4. (Optional) Use the provided `mpv.conf` and `input.conf` in your root mpv folder for the best hardware decoding and custom shortcuts.

## Key Bindings

| Key | Action |
| --- | --- |
| `O` | Toggle File Browser |
| `TAB` | Toggle Playlist |
| `C` | Toggle Chapters Menu |
| `A` / `Shift+A` | Cycle / Toggle Audio Menu |
| `S` / `Shift+S` | Cycle / Toggle Subtitles Menu |
| `Ctrl+S` | Take clean screenshot (no UI/Subtitles) |
| `.` / `,` | Step forward/backward frame-by-frame |
| `Typing` *(in Browser)* | Search files/folders instantly |

## Credits
* [maoiscat/mpv-osc-modern](https://github.com/maoiscat/mpv-osc-modern) - Original OSC script.
* [cyl0/ModernX](https://github.com/cyl0/ModernX) - ModernX fork.
