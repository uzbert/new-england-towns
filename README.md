# Six small towns, one late-fall weekend

A single-page presentation comparing Wickford, Lenox, Stockbridge, Great Barrington, Kennebunkport and Chatham for a Thanksgiving-to-December getaway. It is one file, `index.html`, with no build step and no dependencies.

## Put it on GitHub Pages

1. Create a new repository on GitHub (for example `new-england-towns`). It can be public or private, but Pages on a free account needs a public one.
2. Upload `index.html` to the root of the repository. Use **Add file > Upload files**, then commit.
3. Open **Settings > Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the `main` branch and the `/ (root)` folder, and save.
5. Wait a minute or two. The site appears at `https://YOUR-USERNAME.github.io/new-england-towns/`. The Pages settings screen shows the exact link.

To update it later, upload a new `index.html` over the old one and commit.

## How to present it

- Press **Start presenting** (top right) for full screen. Use the left and right arrow keys, or Page Up and Page Down, to move between slides. The dots on the right also jump to a slide on wide screens.
- On each town slide, use the tabs for the case, pros and cons, where to stay, and things to do. Use the **Add to shortlist** button to mark favorites.
- The last big slide, **Which one wins for you?**, re-ranks the towns as you move the sliders.

## Photos

Photos load live from Wikimedia Commons when the page is opened, and each one is credited with its author and license under the picture. If the network blocks Wikimedia, the page shows a color panel instead of a photo.

To use your own pictures:

1. Put image files in an `images` folder in the repository.
2. In `index.html`, find the town you want and fill in its `customImages` list:

```js
customImages:[{src:"images/lenox1.jpg", credit:"Photo by me"}, {src:"images/lenox2.jpg", credit:"Photo by me"}],
```

Your pictures replace the Commons photos for that town.

## Editing the content

Everything lives in the `TOWNS` list near the top of the script: the summary, pros and cons, lodging pick, activities, sources, and the scores that drive the ranking. Each claim has a `s:[…]` list of source numbers that become the superscript links.

## What to verify before you book

- Event dates for 2026: Wickford’s Festival of Lights and Lenox’s Winterland are expected from prior years. Stockbridge, Kennebunkport and Chatham have published 2026 dates.
- The Wainwright Inn in Great Barrington (a real-estate listing for it turned up).
- Winter hours at restaurants in Kennebunkport and Chatham.
- Drive times are rough estimates from New York City, not from the sources.

Research current as of November 1, 2026.
