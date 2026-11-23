# GEDCOM Viewer — AI Agent Instructions

## What This Repo Is

A single-file family tree viewer for GEDCOM files. Published at https://theo-armour.github.io/gedcom-viewer/. The family files and Wiki biographies it shows live in the [genealogy repo](https://github.com/theo-armour/genealogy).

## Organization

- [index.html](index.html) — the whole app: plain HTML, CSS and JavaScript, no libraries, no build step.
- [README.md](README.md) — what it does, and the `## Changelog`.
- [sample-ged-files/](sample-ged-files/) — sample trees offered in the File menu, kept as downloaded; their sources and credits are in its README. A new sample goes in the folder, in `FILES` in `index.html`, and in that README's table.
- [0-gedcom-viewer-agenda.md](0-gedcom-viewer-agenda.md), [0-gedcom-viewer-journal.md](0-gedcom-viewer-journal.md) — to-dos and dated notes (newest first).

## Conventions for Edits

- **Release cycle, one `index.html.bak`.** Releases are tagged on GitHub (e.g. `v1.0.0`). Don't make timestamped backups. Instead, before the first edit to `index.html` in a session, copy it to `index.html.bak`, replacing the old one. Other files (README, agenda, journal) need no backup.
- **Revised and version.** Update `<meta name="revised">` on every edit. Change `<meta name="version">` and the `v…` in the footer only for a release.
- **Journal, not README.** Record each change as a short bullet under today's date in [0-gedcom-viewer-journal.md](0-gedcom-viewer-journal.md), not in the README changelog.
