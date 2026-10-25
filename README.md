# China & Hong Kong Interactive Trip Plan

A generic, interactive 21-day / 20-night travel guide through Beijing, Xi'an,
Shanghai and Hong Kong — built as a portfolio side project for fun and learning.

- **21 days, 20 nights, 4 cities, 20 places, 3 train legs**
  - Beijing — Days 1-7, 7 nights
  - Xi'an — Days 8-12, 5 nights
  - Shanghai — Days 13-17, 5 nights
  - Hong Kong — Days 18-21, 3 nights
- Day-by-day breakdown per city, with a photo for every place.
- Interactive map, city filters, search, and a planned-places checklist.
- **Export to Google Maps:** download KML or CSV and import it into
  Google My Maps to create a saved map/collection, plus per-city
  Google Maps directions links. Google offers no public API for a website
  to silently create a Saved List in a personal Google Maps account, so
  the My Maps import is the official workaround — and the site says so.

## Scope note

This is a generic guide, not a personal trip. It uses only the 20 places
from the source itinerary, contains no calendar dates and no home
destination, and adds no places beyond that list. Days 6, 7, 12 and 21
are labelled free/buffer days.

## Map: BYO Mapbox token

The map works with no key at all, using free Leaflet / OpenStreetMap tiles
by default. If you have a Mapbox account, paste **your own public (`pk.`)**
token in the "Prefer Mapbox?" panel to switch to Mapbox GL styles.
No token is baked into this site and no token is stored or sent anywhere
except to Mapbox from your own browser tab. Never use a secret (`sk.`)
token in a browser page.

If you deploy this yourself and want Mapbox on by default, create a
dedicated project token with public scopes only and restrict it to your
deployed domain in the Mapbox dashboard.

## Run it

Open `index.html` in a browser, or serve this folder with any static
file server. No build step, no backend, no authentication is required.
