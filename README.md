# Sofia · Kindle browser test

A tiny, click-through prototype for DM2601 Group 9 (theme: Rituals), built to check whether a hi-fi prototype can run in the Kindle's built-in (experimental) browser.

**HMW:** How might we help Sofia sustain her personally meaningful reading ritual despite the changing conditions of shared public transit?

## What's in it

| Page | What it tests |
|---|---|
| `index.html` | Home: continue reading on the green line |
| `reading.html`, `reading-2.html` | Reading + page turn (e-ink refresh time), tap a sentence to highlight |
| `saved.html` | Highlight tagged with Tunnelbana line; reads `?n=` via ES5 JavaScript |
| `line.html` | Inline SVG line map with tappable links, shared highlights |
| `crowded.html` | Standing / one-handed mode with large type |
| `highlights.html` | Highlights grouped by line |
| `arrived.html` | End-of-ride summary |
| `test.html` | Capability report: JS features, CSS flex/grid/variables, localStorage, CPU loop, tap latency, user agent |

Design constraints: plain HTML/CSS, every interaction is a page link, no animation, grayscale only (lines use ● ■ ▲ + label, never colour alone), ES5-only JavaScript.

## Run it on a Kindle

1. Enable GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
2. On the Kindle: ⋮ menu → Experimental Browser → type `https://<username>.github.io/sofia-kindle-test/`.
3. Open **Run browser capability test** at the bottom of the home page and photograph the results.

All book text is original placeholder writing.
