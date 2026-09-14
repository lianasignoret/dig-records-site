# Dig Records, the shop's site

One static page (`index.html`), French first with an English toggle, in the Dig brand. Everything unknown is a
visible orange placeholder in square brackets: address, hours, phone, email, Instagram, opening date, genres to
complete, Laurent's bio and interview, the legal notice. Edit the HTML directly; the copy is inline next to its
English twin (`data-fr` / `data-en` spans).

To do before it goes live: replace the placeholders, put the shop's coordinates in the OpenStreetMap iframe and
the JSON-LD, drop a square photo of the shop and a portrait (replace the two `.photo` boxes with `<img>`), create a
Formspree form and paste its endpoint in the form's `action`, set the domain in the JSON-LD `url`.

Hosting: any static host serves this file as is. GitHub Pages from this folder or Netlify's drag-and-drop are free
and need no Lovable credits; if Lovable is used, the whole prompt is "Host this index.html as is, at [domain]".
