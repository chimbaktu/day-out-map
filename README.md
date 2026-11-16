# Day Out Map

A Google Maps view of the places and events from Day Out Finder.

- `index.html` is the map page, served by GitHub Pages.
- `config.js` holds the Google Maps browser key. That key is public by design and is protected by its website restriction in Google Cloud.
- `data/places.json` holds the places list.
- `data/events.json` holds upcoming events. The nightly Day Out Finder update refreshes it.

The saved list, ratings and memories stay in the private app and are never stored here.
