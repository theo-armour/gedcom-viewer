# GEDCOM Viewer Journal

## 2026-11-21

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
