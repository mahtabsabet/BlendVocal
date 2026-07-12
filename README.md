# Blend Vocal — blendvocal.ca

The website for **Blend Vocal Association of Calgary**, a vibrant auditioned treble choir.

A plain static site (HTML + CSS + a little JS) hosted on **GitHub Pages** at
[blendvocal.ca](https://blendvocal.ca). No build step — what's in the repo is what ships.
The `.nojekyll` file tells GitHub Pages to serve the files as-is (no Jekyll processing).

## Design — "Twilight"

- **Palette:** a dusk gradient running plum-purple → teal (Blend's brand colours) with a
  warm apricot "sunset" glow, over warm ivory.
- **Type:** Fraunces (display serif) + Mulish (body), loaded from Google Fonts.
- **Themes:** adapts to light and dark automatically (`prefers-color-scheme`).

## Structure

```
index.html             Home
events.html            Season schedule + featured concert (the "events calendar")
listen.html            Recordings
about.html             About + Music Director bio
auditions.html         How to join
assets/css/style.css   Design system (all shared styling)
assets/js/site.js      Header scroll, mobile menu, footer year, logo fallback
assets/img/            Photos, posters, favicon
assets/audio/          Concert recordings
```

## Updating things

- **Add or change an event:** edit the `<article class="event">` blocks in `events.html`
  (and the season preview in `index.html`). Copy an existing block, then change the date,
  title, category tag and details.
- **Swap a photo:** drop the new file in `assets/img/` and update the `src` in the page.
- **The logo:** add the microphone logo as `assets/img/blend-logo.png` and it appears
  automatically in the header and footer. Until then, a simple mark stands in.
- **Add a recording:** drop the `.mp3` in `assets/audio/` and copy a `<div class="track">`
  block in `listen.html`.

## Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

No dependencies to install.
