# Pocket Player

A private, offline music player that runs entirely in your browser.

Add your own **MP3**, **FLAC**, **M4A**, or **WAV** files. Nothing is uploaded to a server — your library stays on your device.

## Features

- Local library (IndexedDB)
- Tag reading — title, artist, album, cover art, lyrics
- Playlists with covers
- Queue, shuffle, repeat, ±10s skip
- Lock screen controls (Media Session)
- Themes: Sleek, iPod Classic, Mac Aqua
- Light / Dark / System appearance

## Usage

1. Open the site (or **Add to Home Screen** for an app-like experience).
2. Tap **+ Add** and choose songs from Files.
3. Play tracks, build playlists, and edit info from the **⋯** menu.

> Best in a recent Chrome, Safari, Firefox, or Edge. FLAC support depends on the browser.

## Hosting

This is a single static `index.html` file. You can host it on any static host:

- [GitHub Pages](https://pages.github.com/)
- Netlify
- Cloudflare Pages

On GitHub Pages, put the player at the repo root as `index.html`, then enable **Settings → Pages** (branch: `main`, folder: `/ root`).

Each visitor’s music is stored only in **their** browser.

## Privacy

Audio and metadata never leave the device. Clearing site data removes the library.

## License

Free to use and modify for personal projects.
