# Trident Tours — interactive homepage

A single-page homepage concept for [tridentours.com](https://tridentours.com).

The hero is an illustrated Miami waterfront at dusk, seen from the backyard lawn:

| # | Object | Leads to |
|---|--------|----------|
| 01 | Modern villa on the shoreline (right) | Homes · `/services/homes` |
| 02 | Yacht moored at the dock (left) | Yachts & Marine · `/services/yachts` |
| 03 | Skyline in the distance (centre) | Commercial · `/services/commercial` |
| 04 | Private jet overhead | Private aviation · `/contact` |

Hovering an object dims the rest of the scene, outlines the object with a brass glow and shows a label.
Clicking it flies the camera in and opens a panel with copy, highlights and links into the live site.
The chips at the bottom do the same thing, for touch screens and keyboards. Esc or "Back to the shore" returns.

Everything is in `index.html`: inline SVG, CSS and vanilla JS, with no build step. Open the file in a browser to view it.
