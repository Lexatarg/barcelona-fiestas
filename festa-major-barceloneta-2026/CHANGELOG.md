# Changelog

All notable changes to this project are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

For a content site rather than a library, the versions are read as:

- MAJOR for a redesign or restructure that changes how the page is navigated or read.
- MINOR for new features, new sections, or a new language.
- PATCH for corrections to times, venues, names, translations, or bug fixes.

## [Unreleased]

## [1.3.4] — 2026-10-03

### Changed
- English text now uses US spelling and vocabulary (Merriam-Webster), for
  example program, neighborhood, theater, labor of love and soccer. Catalan
  names such as Centre Cívic stay as they are.

## [1.3.3] — 2026-10-02

### Changed
- All running text (introduction, event descriptions, tips, essentials and
  footer) now wraps at one width, as on the index.
- Castilian now addresses the reader formally (usted) throughout.
- Footer: a shorter first paragraph naming the official source and linking it
  for the full programme and any last-minute changes, and a second paragraph
  saying the page is hosted on GitHub Pages, with a link to the GitHub Privacy
  Statement.

## [1.3.2] — 2026-10-02

### Changed
- The footer now starts "Això és un projecte personal" in Catalan and "Esto es
  un proyecto personal" in Castilian, matching the English wording.

## [1.3.1] — 2026-10-02

### Changed
- Small text (the line above the title, labels, tags, weekdays, the version
  number and the buttons in the directions sheet) now uses normal letter
  spacing instead of spaced-out letters.

## [1.3.0] — 2026-10-02

### Added
- "Add to calendar" on every event. The page builds an .ics file in the
  browser, in the language the reader has chosen, with the Barcelona time
  (including events that run past midnight), the title, the place with its
  address and coordinates, the description, tags and tips, a link to the guide
  and a link to the official programme. Nothing is sent anywhere.

## [1.2.5] — 2026-10-01

### Changed
- The chosen language is now stored under "bcnf-lang", the same key as the
  index and the other guides, so it carries over between pages. A choice saved
  earlier under "fmb-lang" is still read.

## [1.2.4] — 2026-10-01

### Changed
- English dates now use the month-day order, as in "Friday, October 2" and
  "October 2–12, 2026". Catalan and Castilian keep day-month order, and the
  Castilian abbreviation for September follows the RAE ("sept.").

## [1.2.3] — 2026-10-01

### Changed
- The date number keeps the same gap to its heading whether it has one digit or
  two, at every screen size.
- The header, day navigation, page content and footer now share one left edge.

## [1.2.2] — 2026-10-01

### Changed
- Headings and titles use more open letter spacing, so they are easier to read.
- The date number sits in a fixed column aligned with the timeline, so every
  day's heading starts on the same line at any screen size, with one-digit and
  two-digit dates alike.
- The footer now says plainly that the page does not use cookies or collect
  any personal data.

## [1.2.1] — 2026-10-01

### Fixed
- Citymapper links now open with the destination filled in. Citymapper needs
  coordinates rather than an address, so each venue now carries them, taken
  from Barcelona's open data and OpenStreetMap address points. Plaça d'Hilari
  Salvadó and Plaça d'Antoni Genescà i Coromines offer the other three maps
  apps only.

## [1.2.0] — 2026-10-01

### Added
- The first six days of the festival, from the opening speech on Friday
  25 September to Wednesday 30 September, so the guide now covers the whole
  programme.
- The Punt Lila on Saturday 26 September in Plaça de la Barceloneta.
- Venues for the new days, including the church of Sant Miquel del Port, the
  Port Vell street market and Plaça d'Antoni Genescà i Coromines.

### Changed
- The essentials now include the opening speech and the havaneres.
- The note under the places describes the Barceloneta Residents exhibition
  that opened on 17 September.

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

## [1.0.0] — 2026-09-25

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

[Unreleased]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.5...HEAD
[1.2.5]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.4...festa-major-barceloneta-2026-v1.2.5
[1.2.4]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.3...festa-major-barceloneta-2026-v1.2.4
[1.2.3]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.2...festa-major-barceloneta-2026-v1.2.3
[1.2.2]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.1...festa-major-barceloneta-2026-v1.2.2
[1.2.1]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.2.0...festa-major-barceloneta-2026-v1.2.1
[1.2.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.1.0...festa-major-barceloneta-2026-v1.2.0
[1.1.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/festa-major-barceloneta-2026-v1.0.0...festa-major-barceloneta-2026-v1.1.0
[1.0.0]: https://github.com/Lexatarg/barcelona-fiestas/releases/tag/festa-major-barceloneta-2026-v1.0.0
