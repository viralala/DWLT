# Department of We Love Tana (DWLT)

A playful interactive storytelling site inspired by pulse-driven micro-sites. Single-file static site built with GSAP and the Web Audio API.

## Files
- `index.html` — the full site (open in a modern browser).

## Run locally
1. Open `index.html` in your browser (double-click or serve with a static server).
2. First click anywhere to enable audio (browser autoplay policy).

## Background music
- Double-click the top-left sound button to choose a local audio file (MP3/AAC). The site will play it on loop and silence other sound effects.
- Or place a file named `bg-music.mp3` or `Cold_Play_-_Yellow_Accoustic_(mp3.pm).mp3` next to `index.html` and reload.

## Deploy to Vercel
1. Import the `viralala/DWLT` repo in the Vercel dashboard and deploy (no build step required).
2. Or use the Vercel CLI:
   ```bash
   npm i -g vercel
   vercel login
   cd path/to/DWLT
   vercel --prod
   ```

## Development notes
- `AudioManager` in `index.html` handles background music and SFX; enabling music-only mode silences procedural SFX.
- Mochi (the agent) is draggable — click/touch and drag the mascot.

## License
This repo contains user-provided assets; choose a license if you plan to share publicly.
