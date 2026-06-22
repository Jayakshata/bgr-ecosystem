# The BGR Ecosystem — Cinematic Pitch

A self-playing, voice-narrated cinematic web experience: from bare greenfield land to a living, automated factory — one ecosystem, for Tamil Nadu.

**▶ Live:** https://jayakshata.github.io/bgr-ecosystem/

Anchor: **BGR NEO**. Partners: **ANITA · NIKITHA · ENEXIO · BGR NEO**.

## Run locally
```bash
python -m http.server 8000
# open http://localhost:8000  →  press “Begin”  ·  press F for fullscreen
```

## Stack
Plain HTML / CSS / JS · [GSAP](https://gsap.com) for motion · per-line narration audio that auto-syncs on-screen text to the voice-over. No build step — open `index.html` over a local server (audio needs `http://`, not `file://`).
