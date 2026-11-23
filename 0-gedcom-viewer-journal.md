# GEDCOM Viewer Journal

## 2026-11-22

* **Only the master tree** — for privacy, the File menu no longer lists every `.ged` in the genealogy repo; the GitHub file listing is gone. The menu now holds the 2026 master tree and the samples
* **Sample files** — added `sample-ged-files/kennedy.ged` (Chronoplex's Kennedy sample, unzipped from its `.gdz`; GEDCOM 7.0, 70 people) to sit beside `shakespeare.ged` (same as the current webtreeprint.com download). Both are in the menu as "sample: …" and load from beside the page. Maria Skłodowska-Curie isn't a file: Topola reads her straight from the WikiTree API
* **New default file** — the viewer now opens on the hand-maintained master tree, `GEDCOM-files/2026/2026-11-22-armour-genealogy.ged`, starting from me. The MyHeritage export stays in the fallback File menu
* **Ten new biographies linked** — added the great- and great-great-grandparents with new Wiki pages to the Wiki list: Aurelia Chamberlin Burrage, Barbara Allison Armour, Erastus Foote Jr, George Claiborne Watkins, Harriette Cobb Foote Armour, Ida Watkins Shirk, Mary W. Marshall Shirk, Olga Nikolaevna Kudasheva, Sarah Page Wood Foote and Sophia Fulton Watkins. None has a photo yet. The list now has 55 entries
* **GEDCOM file paths** — the genealogy repo moved its GEDCOM files from `Online-Genealogy/gedcom-files/` to `GEDCOM-files/2025/`. The default file and the three fallback files now point there, and menu labels leave off `GEDCOM-files/`

## 2026-11-21

* **Load by URL** — a 🔗 URL… button loads a GEDCOM file from any web address that allows it. GitHub `blob` page links are turned into raw file links. The URL is added to the File menu and remembered next time. Local files still open with 📂 Open… or by dragging onto the tree
* **Every GEDCOM file in the File menu** — on load the viewer asks GitHub for every `.ged` in the genealogy repo (10 today, up from 3), including the Fiverr and Wiki exports. Menu entries are repo paths, with `Online-Genealogy/gedcom-files/` left off. Falls back to the three built-in files if GitHub can't be reached
* **Release 1.1.0** — Octocat link, title clean reload, biography links fixed and opening in a new tab. Version bumped in the `<meta name="version">` tag and the footer
* **.gitignore** — `*.bak`, so `index.html.bak` stays on my computer
* **Octocat link** — a GitHub Octocat icon before the title links to the source on GitHub. The header now reads Octocat, "GEDCOM Viewer", then 🌳
* **Title clean reload** — clicking the title clears the saved settings and reloads the page on the default file
* **Biography links** — Wiki links now add `?owner=theo-armour&repo=genealogy`, so TooToo always opens the genealogy repo instead of the gedcom-viewer repo
* **Biography pages** — links now go to each person's `README-<folder>.md` (spaces as dashes) instead of `<folder>.md`, which didn't exist. Fixed Sergei Vladimirovich Kudashev's page and Norman Armour Sr's photo path. All 45 Wiki entries checked against the files. The link opens in a new tab, so the tree stays put
* **AGENTS.md** — added agent instructions. No timestamped backups now that releases are tagged; instead a single `index.html.bak`, replaced at the start of each editing session
* **Release 1.0.0** — first release of the viewer since moving it out of the genealogy repo. Published on GitHub as tag [v1.0.0](https://github.com/theo-armour/gedcom-viewer/releases/tag/v1.0.0)
* **Version marker** — added `<meta name="version" content="1.0.0">` and `v1.0.0` in the footer of `index.html`
* **Changelog** — started a `## Changelog` section in the README
