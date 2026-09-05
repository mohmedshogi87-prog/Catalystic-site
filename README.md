# Catalystic site — source

The 50 HTML pages above are generated. Edit content, rebuild, everything stays consistent.

    python3 build.py

- `theme.py`      — CSS, shared `<head>`, JavaScript
- `content_en.py` — every word of English copy
- `content_ar.py` — every word of Arabic copy
- `build.py`      — page templates, JSON-LD, sitemap

Add a service, case study or post to the matching list in **both** content files
with the same `slug`. Nav, footer, dropdown, related grids and sitemap follow.

## Eight case studies, in homepage order
GMIS · Hola Vitamins · DIEC · Fine's Health · Majesty Education · EAS School ·
The Canadian Academy · Omnia Education

## Before you publish
1. Client logos in place of the text plates on the homepage (with permission).
2. A photograph in place of the `MB` initials (homepage founder band, About sidebar).
3. Real Google review score and count, or delete the `.rev-band` block.
4. Every testimonial confirmed in writing.
5. Delete the note boxes at the bottom of privacy.html and terms.html, both languages.
6. A 1200x630 `og-image.jpg` at the site root.
7. Confirm the office address (see the open questions in chat).
