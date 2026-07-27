# AITECH – Dark Landing Page

Interaktive Landingpage für AITECH (KI-gestütztes Gold Copy-Trading) mit umschaltbarem Hell/Dunkel-Design.

## Nutzung

Keine Build-Tools nötig — `index.html` direkt im Browser öffnen.
Internetverbindung erforderlich (CDN: Three.js, GSAP, Google Fonts).

## Struktur

```
index.html      – komplette Seite (HTML + CSS + JS inline)
assets/         – generierte Bilder (fal.ai GPT-Image-2), Hero-Loop-Video (Seedance 2.0), Logo
```

## Features

- **Theme-Switcher** im Header (Hell/Dunkel), Auswahl wird in `localStorage` gespeichert
- **Hero**: Video-Loop mit Auslauf-Maske, überlagernde Headline, Forex-Ticker, Three.js-Partikelfeld
- **GSAP/ScrollTrigger**: Scroll-Reveals, Count-Up-Zahlen, Chart-Animationen
- **4-Wochen-Rückblick** als Akkordeon, alle Inhalte 1:1 von der [Live-Seite](https://jandkosian.github.io/aitech/)
- Responsive, `prefers-reduced-motion` wird respektiert

## Design-Tokens

Beide Themes laufen über CSS-Variablen in `:root` bzw. `html.theme-light` (oben in `index.html`).
Akzente: Lime `#c9f24b` · Gold · dunkle Basis `#070806` / helle Grau-Basis `#eef0ea`.
