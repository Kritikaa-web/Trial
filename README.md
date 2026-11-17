# Kritika Nanwani — Personal Resume Website

A single-page resume site for **Kritika Nanwani**, a science student from Seoni
preparing for commercial pilot training. Built from scratch with semantic HTML5
and hand-written CSS — no frameworks, no build step.

**Live site:** https://kritikaa-web.github.io/WebDev_MidTerm/
**Repository:** https://github.com/Kritikaa-web/WebDev_MidTerm

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole site — hero, about, education, aviation, skills, achievements, sport, contact |
| `style.css` | All styling, organised in 19 commented sections |
| `favicon.svg` | "KN" monogram with a horizon line |

## Design direction

An aviation-inspired dark theme ("Flight Deck"): near-black surfaces, a sky-blue
structural accent, amber for action and emphasis, and mono-spaced labels that read
like instrument data. The theme is carried by hairlines, grid lines and readouts
rather than literal aviation graphics.

- **Type:** Space Grotesk (display), Inter (body), JetBrains Mono (labels and scores)
- **Palette:** ink `#08090B` · panel `#0F1216` · sky `#74BAE9` · amber `#F0A63C` · paper text `#ECE9E3`
- **Layout:** fixed blurred header, display-grid hero, CSS-grid card systems,
  dashed timeline, sticky fact file, full-bleed section rhythm
- **Responsive:** three breakpoints at 1020px, 900px and 820px; the mobile menu
  runs on a checkbox and a `:checked` sibling selector, with seven lines of JS
  to close it after a link is tapped
- **Accessibility:** skip link, visible focus rings, labelled landmarks, 44px+
  interactive targets, `prefers-reduced-motion` support, and a print stylesheet
- **Print:** the "Print / Save as PDF" button drops the dark theme and lays the
  resume out on white for a clean paper copy

## CSS techniques used

Element, class and ID selectors · custom properties · `clamp()` fluid type ·
Flexbox and Grid · absolute/fixed/sticky positioning · pseudo-elements and
pseudo-classes · attribute selectors · `:focus-visible` · `:checked` navigation ·
dashed timeline connectors · animated gauges · media queries · print CSS ·
reduced-motion queries.

## Placeholders to replace before sharing

- Email `abc@gmail.com` and phone `00000 00000` in `index.html` (they are
  intentional placeholders for this submission)

## Run locally

No tooling required — open `index.html` in a browser. For a local server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000
