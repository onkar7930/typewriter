# Typewriter

A single-file, distraction-free typewriter simulator for your Mac. No install, no build step — one HTML file.

## Launch

1. Open `index.html` in **Chrome** (recommended — needed for saving to a configured folder). Double-click it, or drag it onto Chrome.
2. Click the fullscreen icon (top-right) or press `⌃⌘F`.
3. Start typing. A sheet of paper is already fed in.

## The experience

- Typebars swing up and strike the paper exactly where the real key sits on a QWERTY keyboard — left-hand keys strike from the left, right-hand keys from the right.
- Every keystroke has a synthesized mechanical thock; space, backspace, and returns each have their own sound. All audio is generated live — no sound files.
- The carriage moves the paper left as you type; `Return` slides it back with a zip, ratchet, and line feed.
- A margin bell dings 6 characters before the end of the line.
- **Backspace is authentic by default**: it moves the carriage back but never erases. Typing over a struck spot overprints both characters (the saved file keeps the newest one). Switch to "Modern" in Settings if you want erasing.
- Ink is slightly irregular — jitter, rotation, and uneven darkness — like a real ribbon.

## Saving

- Press `⌘S` or hover the mouse and click the save icon. Your page is exported as a `.md` file.
- **Configure the output folder** in Settings → Saving → "Choose…". Chrome will ask permission once; after that every save writes straight into that folder. The choice is remembered between sessions.
- Filename pattern supports `{date}` and `{time}` tokens.
- In Safari/Firefox (no folder API) saving falls back to a file picker or download.

## Settings (gear icon)

- Output folder and filename pattern
- Typebar animation on/off, QWERTY spread, hand origin depth, strike speed
- Sound on/off, volume, margin bell
- Type size, characters per line, ink darkness, ink irregularity
- Backspace behaviour (authentic / modern), auto carriage-return
- "Reset to real-life defaults" restores everything

## Notes

- The typewriter font (Special Elite) loads from Google Fonts; offline it falls back to Courier New.
- Arrow keys nudge the carriage/platen (handy for overstriking corrections in authentic mode). Tab jumps 5 spaces.
- The "new sheet" icon feeds in fresh paper (warns if unsaved text is on the page).
