# Birthday Story

A one-page, scroll-driven birthday website.

## Quick start (3 things to do)

1. **Her name** — open `js/config.js` and set `friendName`.
2. **Photos** — drop six images into `assets/photos/` named exactly:
   - `photo-1.jpg` first-year college memory
   - `photo-2.jpg` travelling together
   - `photo-3.jpg` random / funny photo
   - `photo-4.jpg` best friendship photo
   - `photo-5.jpg` VOIS achievement / celebration
   - `photo-6.jpg` one final photo of you two

   Any missing photo simply shows its elegant placeholder.
3. **Music (optional)** — put an `.mp3` at `assets/music/song.mp3`. It never autoplays; the music button (bottom-left) plays/pauses.

## Open it

Double-click `index.html`, or host the folder for free on Netlify Drop, GitHub Pages or Vercel, then send her the link.

## Structure

```
birthday-site/
├── index.html
├── css/style.css
├── js/
│   ├── config.js      <- edit name + music path
│   ├── particles.js   <- floating hearts and stars
│   ├── confetti.js    <- confetti (VOIS + finale only)
│   └── main.js        <- scroll reveals, typewriter, progress, modak, music
└── assets/
    ├── photos/
    └── music/
```

## Tweaking

- Colours and fonts: variables at the top of `css/style.css`.
- Wording: all in `index.html`.
