# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For a content site rather than a library, the versions are read as:

- MAJOR for a redesign or restructure that changes how the page is navigated or read.
- MINOR for new features, new sections, or a new language.
- PATCH for corrections to times, venues, names, translations, or bug fixes.

## [Unreleased]

## [1.1.0] — 2026-10-01

### Added
- A light and dark mode button next to the language picker. The page still
  follows the device setting until the reader chooses, and the choice is
  remembered across every guide in the collection.

### Changed
- The blue bands under the header and above the footer are now thin lines
  instead of thick stripes.
- The year in the header keeps the same light blue in dark mode, so it stays
  easy to read.
- Moved into the barcelona-fiestas collection. The page now lives at
  lexatarg.github.io/barcelona-fiestas/festa-major-barceloneta-2026/ and its version tags are
  prefixed with the guide's folder name.

## [1.0.0] — 2026-10-01

### Added
- First release, covering Thursday 1 to Sunday 4 October 2026 in Catalan,
  Castilian and English, with the language picked from the browser and
  remembered between visits.
- Five essentials, a timeline for each day, a list of venues and a practical
  section on fire run safety, the Punt Lila, public toilets and emergency
  numbers. Every item is taken from the official programme.
- A directions sheet for every venue that opens Google Maps, Apple Maps,
  Citymapper or OpenStreetMap, and can copy the address.
- Scrollspy navigation and a light and dark colour scheme.

### Notes
- Built on the same layout as the La Mercè 2026 guide, recoloured after the
  official Barceloneta programme.
- Venues are searched by address rather than by coordinates, so the maps app
  resolves the exact spot.

[Unreleased]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.1.0...HEAD
[1.1.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.0.0...festa-major-barceloneta-2026-v1.1.0
[1.0.0]: https://github.com/Lexatarg/barcelona-fiestas/releases/tag/festa-major-barceloneta-2026-v1.0.0
