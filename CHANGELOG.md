# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For a content site rather than a library, the versions are read as:

- **MAJOR** — a redesign or restructure that changes how the page is navigated or read.
- **MINOR** — new features, new sections, or a new language.
- **PATCH** — corrections to times, venues, names, translations, or bug fixes.

## [Unreleased]

## [1.1.0] — 2026-09-23

### Added
- Interactive map (Leaflet + CARTO basemap) replacing the single-marker embed.
  All fifteen venues now appear as numbered pins, pannable and zoomable, each
  with a popup naming what happens there.
- Directions chooser. Every venue and timeline entry opens a sheet offering
  **Google Maps**, **Apple Maps**, **Citymapper** and **OpenStreetMap**, plus a
  copy-coordinates button, instead of forcing one provider.
- "Show on map" control on each venue, which scrolls to the map and opens that pin.
- Scrollspy: the sticky day nav now highlights the section currently in view and
  scrolls itself to keep the active day visible.
- Dark-mode map tiles, switching automatically with the system theme.
- Open Graph tags for link previews when shared.
- Version number displayed in the footer.
- Platja del Somorrostro added as a venue — the officially recommended vantage
  point for the drone show and the Espigó del Gas fireworks.
- This changelog.

### Changed
- All venue coordinates are now explicit latitude/longitude pairs rather than
  place-name search strings, so links resolve identically in every map app.
- Pregó entry now names Meritxell Falgueras as sommelier, per the city council's
  own wording.
- Friday concert entry corrected to "fourteen venues, sixteen stages", matching
  the official figure.
- Privacy note added to the footer: no cookies, no analytics, no tracking.

### Fixed
- Map previously rendered a single generic marker over Barcelona instead of the
  festival venues.

## [1.0.0] — 2026-09-23

### Added
- Initial release: single-page, self-contained guide to La Mercè 2026.
- Chronological timeline for all five days (23–27 September) with times,
  venues, descriptions and practical tips.
- Trilingual interface — Català, Castellà, English — with automatic language
  detection and a saved preference.
- "The essentials" summary of the five headline events.
- Venue list and practical "know before you go" section.
- All times cross-checked against the official programme published by
  Barcelona City Council and betevé.

[Unreleased]: https://github.com/Lexatarg/la-merce-2026/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/Lexatarg/la-merce-2026/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Lexatarg/la-merce-2026/releases/tag/v1.0.0
