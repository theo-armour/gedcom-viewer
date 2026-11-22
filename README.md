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

## My family files

The File menu opens the exports in my [genealogy repo](https://github.com/theo-armour/genealogy). People with a biography in my [family Wiki](https://theo-armour.github.io/genealogy/) are marked 📖 and link to their page.

To add an export, put it in `Online-Genealogy/gedcom-files/` in the genealogy repo and add its name to `FILES` in `index.html`. To add a biography, add a line to `WIKI`.

## How it's made

One file, `index.html`: plain HTML, CSS and JavaScript, no libraries, no build step. Hosted on GitHub Pages.
