# Knit'n'Sip — Arlington Craft Club

Come knit with us in Arlington, VA! A weekly fibre-arts meetup — every Tuesday, 5–7pm, always a walk from an Orange or Silver line Metro station.

**Live site:** https://mscandlen.github.io/arlington-knitnsip/

## Structure

```
index.html              Home
about/                  What the club is and how it works
venues/                 Station map and drink prices
calendar/               Month grids, July–October
events/YYYY-MM-DD/      One page per meetup
clubs/                  Other fibre-arts clubs nearby (not ours) — fibre space, Heurich House, Arlington Central Library
assets/css/styles.css   All styling
assets/images/          Favicon, logo, sheep
404.html                Not-found page
```

## Adding an event

1. Copy any folder in `events/` and rename it to the new date (`events/2026-11-03/`).
2. Edit its `index.html`: date, venue, station, address, prices, blurb.
3. Add the day to `calendar/index.html` (copy an existing `<td class="has">` cell and update the link).

Plain HTML and CSS — no build step. Commits publish automatically via GitHub Pages.
