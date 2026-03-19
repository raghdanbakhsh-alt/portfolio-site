# Raghdan Portfolio Site

Static bilingual portfolio site prepared for GitHub Pages.

## What was updated
- Rebuilt the site structure around confirmed projects.
- Added Arabic / English toggle.
- Added organized project cards and detailed project modal.
- Added image slots and captions for every project entry.
- Added a `projects.json` data file so future edits are simple.

## Important note about project images
The site now includes **image placeholders and full captions/descriptions**, but the real project photos are **not inside the current repository yet**.

To add your real images:
1. Upload image files to a folder like `assets/projects/`
2. Update each project in `projects.json`
3. Set:
   - `cover`: main cover image path
   - `gallery[].image`: detailed image path

Example:
```json
{
  "cover": "assets/projects/gate2/cover.jpg",
  "gallery": [
    {
      "title_en": "Gate 2 facade",
      "title_ar": "واجهة البوابة الثانية",
      "caption_en": "Updated facade and branding view.",
      "caption_ar": "واجهة مطورة مع معالجة الهوية البصرية.",
      "image": "assets/projects/gate2/view-01.jpg"
    }
  ]
}
```

## GitHub Pages
Publish from:
- Branch: `main`
- Folder: `/root`

Expected URL:
`https://raghdanbakhsh-alt.github.io/portfolio-site/`

## Files
- `index.html` → main website
- `projects.json` → project data
- `README.md` → this guide