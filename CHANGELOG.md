# Changelog

Changes to the collection as a whole: the index page and the repository layout.
Each guide keeps its own changelog in its folder.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.13.1] — 2026-10-04

### Changed
- Footer links have no underline until they are hovered, focused or tapped,
  as in the guides.

## [1.13.0] — 2026-10-04

### Changed
- The collection is now called Festes Majors de Barcelona (Fiestas Mayores de
  Barcelona in Castilian) and moves to lexatarg.github.io/festes-majors-barcelona.
- The browser tab shows the name in the chosen language.

## [1.12.0] — 2026-10-04

### Added
- Coming up lists the next major festivals before their guides are ready:
  Clot – Camp de l'Arpa, la Sagrera and Sant Andreu. Each links to its
  official website, opening in a new tab, until its guide is published.

## [1.11.0] — 2026-10-04

### Added
- New guide: Festa Major d'Hostafrancs 2026.

## [1.10.0] — 2026-10-04

### Added
- New guide: Festa Major de l'Esquerra de l'Eixample 2026.

## [1.9.0] — 2026-10-04

### Added
- New guide: Festa Major de les Corts 2026.

## [1.8.0] — 2026-10-04

### Added
- The index footer shows the collection version, like the guides.
- Happening now has a live "ping": a small dot with a circle that grows from it
  and fades. With Reduce Motion turned on, the icon stays still instead.

### Changed
- Guides on the index are ordered by date: latest first in Happening now and
  Past, soonest first in Coming up.
- Coming up is now a dashed circle.

## [1.7.3] — 2026-10-03

### Changed
- English on the index and in the READMEs now uses US spelling and vocabulary
  (Merriam-Webster).
- The index footer now ends "for every major festival included" in all three
  languages.
- README: clearer description of what each guide includes, and a shorter
  Coverage section.

## [1.7.2] — 2026-10-02

### Changed
- The index footer now explains that only a limited number of guides can be
  maintained at a time, that the guides are hosted on GitHub Pages (with a link
  to the GitHub Privacy Statement), and points to each guide's source for the
  full programme and any last-minute changes.
- Castilian on the index now addresses the reader formally (usted).
- README: a new opening line, and new Coverage and Privacy sections.

## [1.7.1] — 2026-10-02

### Changed
- The index footer now starts "Això és un projecte personal" in Catalan and
  "Esto es un proyecto personal" in Castilian, matching the English wording.

## [1.7.0] — 2026-10-02

### Added
- Past is grouped by year, and each year opens and closes when its heading is
  tapped. The most recent year starts open and older years start closed.

### Changed
- The Coming up, Happening now and Past headings, the line above the title,
  the language buttons and the year labels now use normal letter spacing.
- New heading icons: an empty circle for Coming up, a dot inside a circle for
  Happening now, and a filled circle for Past.
- In Past, the year is now a divider: the year followed by a thin line.

## [1.6.0] — 2026-10-02

### Added
- Every guide now has "Add to calendar" on each event, with the same code in
  each page: the .ics file is built in the browser, in the reader's language,
  and nothing is sent anywhere.

## [1.5.1] — 2026-10-01

### Changed
- The index and every guide now store the chosen language under the same key,
  "bcnf-lang", so a language picked on one page is used on the others.

## [1.5.0] — 2026-10-01

### Changed
- A new introduction on the index page, in all three languages, describing
  what the guides offer.
- English dates now use the month-day order, as in "Friday, October 2" and
  "October 2–12, 2026". Catalan and Castilian keep day-month order, and the
  Castilian abbreviation for September follows the RAE ("sept.").

## [1.4.0] — 2026-10-01

### Changed
- The index page has a lighter design: a paper background, black and white type
  and no colour bars, so it does not compete with the guides' own colours.
- Guides are listed as Coming up, Happening now and Past, each with its own
  marker. Past guides keep the same layout in grey.
- "Open the guide" links work like the Directions links inside the guides.
- Section names in Catalan and Castilian now read as a set: Properes, En curs,
  Anteriors and Próximas, En curso, Anteriores.
- The intro, the guide descriptions and the footer share one text width.

## [1.3.0] — 2026-10-01

### Added
- The Festa Major de Sarrià 2026 guide, 2–12 October.
- The index page now groups guides under Happening now, Coming up and Past
  guides, based on each festival's dates in Barcelona time. Past guides are
  still grouped by year.

### Changed
- The footer now says plainly that the pages do not use cookies or collect
  any personal data.
- Headings on the index page use more open letter spacing.

## [1.2.0] — 2026-10-01

### Changed
- The Festa Major de la Barceloneta guide now covers 25 September to
  4 October, and its dates are updated on the index page and in the README.
- The README introduction no longer uses bold text.

## [1.1.0] — 2026-10-01

### Added
- A light and dark mode button on the index page, shared with the guides.

### Changed
- The README describes what each guide contains, and its table links each
  guide's folder and live page.


## [1.0.0] — 2026-10-01

### Added
- An index page in Catalan, Castilian and English that lists every guide,
  newest first and grouped by year.
- The La Mercè 2026 guide, moved from its own repository with its full history.
- The Festa Major de la Barceloneta 2026 guide, moved from its own repository
  with its full history.

[Unreleased]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.5.1...HEAD
[1.5.1]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.5.0...v1.5.1
[1.5.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.4.0...v1.5.0
[1.4.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.3.0...v1.4.0
[1.3.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/Lexatarg/barcelona-fiestas/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Lexatarg/barcelona-fiestas/releases/tag/v1.0.0
