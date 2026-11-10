# Guadalupe · December 12, 2026

A complete, framework-free, single-page microsite. `index.html` contains all HTML, CSS, JavaScript and original SVG artwork. No build, packages, fonts, trackers or image downloads are needed. `.nojekyll` disables Jekyll processing on GitHub Pages.

## Deploy to GitHub Pages

1. Create a GitHub repository (for example `guadalupe-2026`).
2. Upload **index.html**, **.nojekyll** and this README to the repository root. Upload the contents of this folder, not a containing folder.
3. Open repository **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**.
4. Select **main** and **/ (root)**, then **Save**.
5. When GitHub finishes publishing, use the URL shown in Pages, typically `https://YOUR-USERNAME.github.io/guadalupe-2026/`.

No custom domain or workflow is required. Repository visibility and Pages availability depend on your GitHub plan. This package has not been uploaded or published to an account.

## Preview and edit

Open `index.html` in a browser, or serve the folder with any static server. All internal links work under a repository subpath. Update the HTML directly using a text editor. Search for:

- `2026 planning preview`: confirmation notice. Remove or revise only after parish approval.
- `class="day reveal"`: Novena, vigil and feast day schedule. Edit English and the adjacent `lang="es"` Spanish together.
- `EDIT:`: pending route, crossings, support, parking, registration, accessibility, transport, weather and contact details.
- `class="place"`: church locations and map links.
- `:root`: color palette.
- `hero-art`: original Guadalupe-inspired SVG motif.

The text remains readable without JavaScript. JavaScript adds entrance effects and a motion control. System reduced-motion preferences are respected. Native expandable sections, keyboard focus, skip navigation and print styles are included. No custom cursor, autoplay audio, scroll locking or WebGL.

## Content status and sources — checked November 10, 2026

The 2026 event program comes from the supplied brief, **not independent confirmation**. All times are Central. Departure is after the 7 AM Mass and blessing, not at 7 AM. The 5 PM Mass is at the Shrine. Other celebration locations and commissioning/fiesta times remain unspecified rather than inferred. December 3–10 is retained exactly as provided; confirm the Novena date range with the parish.

- Helotes address verified against the parish: https://olghelotes.org/contact-us
- Shrine address verified against the Archdiocese: https://archsa.org/jubilee2025/pilgrimage-sites/
- Provided event reference: https://sites.google.com/view/guadalupanos-olg-helotes/events-eventos/pilgramige-peregrinacion — could not be retrieved independently during this build. Link is retained for organizer updates.
- Aesthetic reference: https://lusion.co/ — inspired the spacious composition and motion approach. No Lusion assets or code are used; no affiliation.

The supplied 2024 handout, historical diagram and two map screenshots were reviewed as background. They are deliberately not published as 2026 navigation. The diagram in this site is a labeled conceptual connection with no geographic claims. Google Maps links identify each church, not an approved pedestrian itinerary. Historical warnings about Loop 1604 and Loop 410 are explicitly identified as historical; 2026 crossings require confirmation.

Before announcing this as final, replace the visible pending details and obtain parish confirmation of times, locations, Archbishop participation, services and route. Add an approved route map only when available, with its date and accessibility description.

## Files

- `index.html`: complete production page, including styles, scripts and vector art.
- `.nojekyll`: GitHub Pages static-file marker.
- `README.md`: deployment, editing and source notes.

Original visual assets and code created for this project. No third-party asset licenses are required. Use of parish names is descriptive; this is an event planning draft.

## Verification

Internal anchors and unique IDs checked; JavaScript syntax and reduced-motion initialization checked. No external runtime assets. Visual desktop/mobile browser QA could not be completed because local preview access was blocked in this environment; review the page in your browser before publication.
