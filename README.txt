# SMD 1.7.1 — Windows Fix (Unofficial)

This is an unofficial Windows‑compatible patch of the abandoned **Spotify Music Downloader (SMD) 1.7.1** project.

The original project was Linux‑focused and no longer maintained.  
I fixed imports, removed Linux‑only modules, and made the program run on Windows.

## What works
- YouTube downloads (`-yv`)
- YouTube Music downloads (`-ym`)
- Query search (`-q`)
- Program launches without Linux errors

## What is broken
- Spotify mode is unstable (YouTube search issues)
- Some Linux‑only features are removed

!!!This version does not include API keys.  
Users must provide their own Genius/Spotify credentials if needed.

## Credits
Original project by [artyshko](https://github.com/artyshko).  
This repository only contains Windows fixes and patches.
