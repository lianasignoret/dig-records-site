# Dig Records, the shop's site

Two static pages (`index.html`, and `story.html` for Laurent's story), French first with an English toggle, in the Dig brand. Filled in (2026-09-14): 7 rue Hoche, 35000 Rennes; Tue–Sat 11:00–19:00 (Mon and Sun closed, to confirm);
contact@digrecords.store; the interview credit (World Records, Volume Two, Iain Wakefield, 2024). Still an orange
placeholder in square brackets: phone, the legal notice (company, SIRET, host), and the portrait photo on the story page. Edit the HTML directly; the copy is inline next to its
English twin (`data-fr` / `data-en` spans).

To do before it goes live: replace the remaining placeholders, drop a portrait on `story.html` (replace the `.photo`
box with `<img>`), create a Formspree form and paste its endpoint in the form's `action`.

Live at **https://lianasignoret.github.io/dig-records-site/** from the repo `lianasignoret/dig-records-site` (public,
GitHub Pages, free). To update: copy this folder's files into that repo and push. A custom domain is one CNAME
record plus the domain in that repo's Pages settings.

Hosting: any static host serves this file as is. GitHub Pages from this folder or Netlify's drag-and-drop are free
and need no Lovable credits; if Lovable is used, the whole prompt is "Host this index.html as is, at [domain]".
