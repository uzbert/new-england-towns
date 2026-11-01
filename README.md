# New England Long Weekend Research

A single-page presentation comparing Wickford, Lenox, Stockbridge, Great Barrington, Kennebunkport and Chatham for an early-December getaway. The target is the first weekend of December (Dec 4 to 6, 2026), with Chatham, a week later, as the outside option. It is one page, `index.html`, plus an `images` folder, with no build step and no dependencies.

Live site: https://uzbert.github.io/new-england-towns/

## Updating the site

The site is served by GitHub Pages from the `main` branch, root folder. Push a change to `index.html` or `images/` and the site updates in a minute or two.

## How to present it

- Press **Start presenting** (top right) for full screen. Use the left and right arrow keys, or Page Up and Page Down, to move between slides. The dots on the right also jump to a slide on wide screens.
- On each town slide, use the tabs for pros and cons, where to stay, and things to do. Use the **Add to shortlist** button to mark favorites.
- The last big slide, **Which one wins for you?**, re-ranks the towns as you move the sliders.

## Photos

Each town has one photo in the `images` folder, named for the town (for example `images/lenox.jpg`). To change one, replace the file, or point the town's `customImages` entry in `index.html` at a different path:

```js
customImages:[{src:"images/lenox.jpg"}],
```

Landscape photos about 2000 px wide work best. A town without a photo shows a color panel.

## Editing the content

Everything lives in the `TOWNS` list near the top of the script: the pros and cons, lodging pick, activities, sources, and the scores that drive the ranking. Each claim has a `s:[…]` list of source numbers that become the superscript links.

## What to verify before you book

- Event dates for 2026: Wickford’s Festival of Lights and Lenox’s Winterland are expected from prior years. Stockbridge, Kennebunkport and Chatham have published 2026 dates.
- Wickford’s lodging pick is an Airbnb. Confirm that Dec 4 to 7 is open and check the total price with fees.
- The Wainwright Inn in Great Barrington (a real-estate listing for it turned up, and its original website no longer works).
- Winter hours at restaurants in Kennebunkport and Chatham.
- Drive times are rough estimates from New York City, not from the sources.

Research current as of November 1, 2026.
