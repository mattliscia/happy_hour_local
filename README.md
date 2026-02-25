# Happy Hour Local

An editorialized, SEO-optimized guide to happy hours, deals, and things to do across the Texas Triangle — Austin, Dallas, Houston, and San Antonio.

## Local Development

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Structure

- `index.html` — Homepage with editorial picks and city navigation
- `austin.html` — Austin city guide
- `dallas.html` — Dallas city guide
- `houston.html` — Houston city guide
- `san-antonio.html` — San Antonio city guide
- `css/styles.css` — Design system built on Pico CSS
- `js/main.js` — Mobile nav, sticky header, scroll reveals

## Tech Stack

- **CSS Framework:** Pico CSS v2 (CDN)
- **Typography:** DM Serif Display + Inter (Google Fonts)
- **Build tools:** None — static HTML/CSS/JS
- **Hosting:** GitHub Pages

## HappyHopper Integration

Each city page includes a HappyHopper list widget in the sidebar showing real-time happy hour deals.
