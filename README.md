# Copenhagen · 6–9 November 2026

Interactive city guide with 37 places across food & drink, culture, history, art, nightlife, design and other sights. Includes four suggested day plans, beer and indoor filters, search, saved favourites, directions, and links to published electronic music events. Nightlife includes clubs and area starting points for Kødbyen and Blågårdsgade, with Jolene and Baggen as additional club options.

## Publish on GitHub Pages

1. Open [Settings → Pages](https://github.com/jenschristianschroder/Cagri-Copenhagen-Nov6/settings/pages).
2. Choose **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.

After GitHub completes deployment, the guide will be available at:
https://jenschristianschroder.github.io/Cagri-Copenhagen-Nov6/

## Editing

`index.html` is self-contained: application styles, place data and Leaflet 1.9.4 are embedded. No build step, account or API key is needed. Search for `window.CPH_PLACES` to edit venues, and `window.CPH_DAYS` to edit day plans. The Leaflet license is included in the HTML. `.nojekyll` enables plain static serving.

Map tiles require internet access and are provided by OpenStreetMap with attribution. Favourites are stored in the visitor’s browser; shared links include place/filter state, not saved favourites.

Sources were checked on 12 October 2026. Pins are approximate locations. Recheck opening hours, event listings, tickets and entry policies before visiting. Monday’s suggestions account for museum closures.

## Verification

Interaction checks passed for all categories, Leaflet marker creation, search, beer/indoor filters, saved places, day plans, deep links, keyboard focus, empty states and map/storage fallback behaviour. The standalone file was independently checked for successful initialization. Visual browser QA and live deployment verification are still pending.
