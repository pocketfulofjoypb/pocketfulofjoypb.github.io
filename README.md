# Pocketful of Joy LLC

Marketing website for Pocketful of Joy LLC — professional photo booth rentals serving Pottstown, PA and surrounding areas.

## Pages

- `index.html` — Home (hero, features, testimonials)
- `about.html` — About / Our Story
- `services.html` — Services & event types
- `gallery.html` — Photo gallery (loads from `data/gallery.json`)
- `contact.html` — Contact info + Google Form quote request

## Tech

- Static HTML site hosted on GitHub Pages
- [Tailwind CSS](https://tailwindcss.com) via CDN
- Plus Jakarta Sans (Google Fonts)

## Editing the gallery

Add or remove photos by editing `data/gallery.json`. Each entry needs a `src`
(path to the image in `images/`) and an `alt` (the caption shown on hover and in
the lightbox). Image file names are case-sensitive on GitHub Pages, so match the
extension exactly (e.g. `.JPG` vs `.jpg`).

## Local preview

Open `index.html` directly in a browser, or serve the folder so the gallery's
`fetch` works:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```
