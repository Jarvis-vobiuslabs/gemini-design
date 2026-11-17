# Trident Tours — interactive homepage

A single-page homepage concept for [tridentours.com](https://tridentours.com).

The hero is a photorealistic Miami waterfront at dusk, seen from the backyard lawn (`assets/hero.jpg`, generated with Higgsfield / GPT Image 2.6):

| # | Object | Leads to |
|---|--------|----------|
| 01 | Modern villa on the shoreline (right) | Homes · `/services/homes` |
| 02 | Yacht moored at the dock (left) | Yachts & Marine · `/services/yachts` |
| 03 | Skyline in the distance (centre) | Commercial · `/services/commercial` |
| 04 | Private jet overhead | Private aviation · `/contact` |

Hovering an object dims the rest of the photo, redraws the object bright with a glowing outline (clipped to a traced polygon) and shows a label.
Clicking it flies the camera in and opens a panel with copy, highlights and links into the live site.
The chips at the bottom do the same thing, for touch screens and keyboards. Esc or "Back to the shore" returns.

On phones the photo can be swiped sideways.

Everything is in `index.html` plus `assets/hero.jpg`: inline SVG, CSS and vanilla JS, with no build step. Open the file in a browser to view it.

The object outlines (`cp-jet`, `cp-yacht`, `cp-city`, `cp-house`) are in the photo's 2688×1520 pixel space. If the photo is replaced, re-trace them.
