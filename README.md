# GEDCOM Viewer

A family tree viewer for GEDCOM files, the standard export format of Ancestry, MyHeritage, Geni, WikiTree and most genealogy programs.

**Live:** https://theo-armour.github.io/gedcom-viewer/

## What it does

* Draws a tree around one person: horizontal, vertical or a fan chart of ancestors
* Colors each of the four grandparent branches, or male and female
* Click a person to see their facts, family, notes, pictures and sources, and their line back to the root. Double-click to make them the root
* Search everyone in the file
* Drag to pan, scroll to zoom
* Saves the drawing as SVG or PNG, or prints it to PDF

## Your own file

Use **📂 Open…** or drag a `.ged` file onto the tree. The file is read in your browser and never leaves your computer.

Or use **🔗 URL…** and paste the web address of a `.ged` file. It's added to the File menu and remembered next time. A GitHub file page link works too. Some sites don't let other pages read their files; for those, download the file and use 📂 Open….

## My family files

The File menu opens the master tree in my [genealogy repo](https://github.com/theo-armour/genealogy), `GEDCOM-files/armour-genealogy.ged`. It's the only family file offered, because the online-service exports hold details of living people. People with a biography in my [family Wiki](https://theo-armour.github.io/genealogy/) are marked 📖 and link to their page.

The menu also has sample trees from [sample-ged-files/](sample-ged-files/): the Brontës, the Gramps example tree, the Kennedys, the US presidents, the royals of Europe (Royal92) and Shakespeare. Their sources and credits are in that folder's README. The menu is the `FILES` list in `index.html`. To add a biography, add a line to `WIKI`.

## How it's made

One file, `index.html`: plain HTML, CSS and JavaScript, no libraries, no build step. Hosted on GitHub Pages.

## Changelog

### 2026-11-21

* Release 1.0.0 — first release, after moving the viewer out of the genealogy repo
* Panel layout and resizing
