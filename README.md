# Dig Records, the shop's site

Two static pages (`index.html`, and `story.html` for Laurent's story) plus `crates.js`, the six crates of fifty records each that the crate effect flips through (edit that file to change them), French first with an English toggle, in the Dig brand. Filled in (2026-09-14): 7 rue Hoche, 35000 Rennes; Tue–Sat 11:00–19:00 (Mon and Sun closed, to confirm);
contact@digrecords.fr; the interview credit (World Records, Volume Two, Iain Wakefield, 2024). No legal notice by choice. Portrait on the story page is `laurent-portrait.jpg`. Edit the HTML directly; the copy is inline next to its
English twin (`data-fr` / `data-en` spans).

To do before it goes live: replace the remaining placeholders, drop a portrait on `story.html` (replace the `.photo`
box with `<img>`), create a Formspree form and paste its endpoint in the form's `action`.

Published from Lovable at **https://dig-crates-rennes.lovable.app/** (project "DIG Records Launch", repo
`lianasignoret/dig-records-launch`, 2026-09-14). There the page is served as is by `src/routes/index.tsx` and
`src/routes/story.tsx` from `src/site/*.html`, with the images and `crates.js` in `public/`; asset paths are absolute
(`/racks.jpg`, `/crates.js`, `/story`). To update: copy `index.html` to `src/site/`, `story.html` to `src/site/`,
other files to `public/`, fix those paths, push to `main`; Lovable syncs it and you click Publish, then Update.
A mirror also runs on GitHub Pages at https://lianasignoret.github.io/dig-records-site/ (repo
`lianasignoret/dig-records-site`, relative paths).

Hosting: any static host serves this file as is. GitHub Pages from this folder or Netlify's drag-and-drop are free
and need no Lovable credits; if Lovable is used, the whole prompt is "Host this index.html as is, at [domain]".
