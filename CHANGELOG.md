# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For a content site rather than a library, the versions are read as:

- MAJOR for a redesign or restructure that changes how the page is navigated or read.
- MINOR for new features, new sections, or a new language.
- PATCH for corrections to times, venues, names, translations, or bug fixes.

## [Unreleased]

## [1.2.0] — 2026-09-23

### Removed
- The interactive map. Every venue already opens in the reader's own maps app,
  so the embedded map added weight and a third-party tile request without
  adding much. The venue list stays, and each entry keeps its directions.
- Leaflet and the CARTO basemap, along with the tile requests they made. The
  page now loads no external scripts at all.
- The emoji favicon.

### Changed
- Rewrote the English copy to read more naturally, following the patterns in
  Wikipedia's "Signs of AI writing". Removed stacked -ing clauses, rule-of-three
  lists, subjectless fragments, and em dashes used where a comma or full stop
  works better. The Catalan and Castilian copy was revised to match, keeping
  the same plain and informative register.
- Section renamed from "Map" to "Places" in all three languages.
- Two tag labels reworded: "Don't miss" is now "Worth planning around", and
  "Grand finale" is now "Closing act".
- The privacy line in the footer now states plainly that the page sets no
  cookies and collects nothing, rather than listing three negatives.

### Fixed
- Spacing in the day headers on narrow screens, where the large date sat too
  close to the heading beside it. The date and text block now have their own
  spacing rules below 400px.
- The hero title, metadata grid and section headings now scale down properly on
  small phones instead of relying on one fixed size.
- The directions sheet scrolls if it runs taller than the screen.

## [1.1.0] — 2026-09-23

### Added
- Interactive map with all fifteen venues as numbered pins.
- Directions chooser offering Google Maps, Apple Maps, Citymapper and
  OpenStreetMap, plus a copy-coordinates button.
- "Show on map" control on each venue.
- Scrollspy, so the sticky day nav highlights the section in view.
- Dark-mode map tiles that follow the system theme.
- Open Graph tags for link previews.
- Version number in the footer.
- Platja del Somorrostro as a venue, the vantage point the council recommends
  for the drone show and the Espigó del Gas fireworks.
- This changelog.

### Changed
- Venue links now use explicit latitude and longitude instead of place-name
  searches, so they resolve the same way in every maps app.
- The pregó entry names Meritxell Falgueras as a sommelier, matching the
  council's wording.
- Friday's concert entry corrected to fourteen venues and sixteen stages.

### Fixed
- The map previously showed one generic marker over Barcelona rather than the
  festival venues.

## [1.0.0] — 2026-09-23

### Added
- First release: a single-page, self-contained guide to La Mercè 2026.
- Chronological timeline for all five days, 23 to 27 September, with times,
  venues, descriptions and practical notes.
- Three languages, Catalan, Castilian and English, with automatic detection and
  a saved preference.
- An "essentials" summary of the five headline events.
- Venue list and a practical section for things worth knowing in advance.
- All times cross-checked against the official programme from Barcelona City
  Council and betevé.

[Unreleased]: https://github.com/Lexatarg/la-merce-2026/compare/v1.2.0...HEAD
[1.2.0]: https://github.com/Lexatarg/la-merce-2026/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/Lexatarg/la-merce-2026/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Lexatarg/la-merce-2026/releases/tag/v1.0.0
