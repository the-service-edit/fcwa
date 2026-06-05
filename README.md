# FCWA site images

Drop your photos into this folder using the exact filenames below. The site reads
them automatically. Until a file exists, that slot shows a warm placeholder panel
with batten lines, so the page never looks broken while you are still loading photos.

Format: JPG (or WebP if you prefer, just change the extension in index.html).
Keep each file under roughly 300 to 500 KB for fast loading. Landscape or portrait
as noted. The site crops to fit, so the focal point should sit near the centre.

## Slots

| File | Used for | Suggested size (px) | Orientation |
|------|----------|---------------------|-------------|
| `images/hero.jpg` | Full hero background | 2000 x 1300 | Landscape |
| `images/about.jpg` | About section portrait / on site | 900 x 1125 | Portrait (4:5) |
| `images/services/01-internal-doors.jpg` | Service card 01 | 800 x 1000 | Portrait (4:5) |
| `images/services/02-skirting-boards.jpg` | Service card 02 | 800 x 1000 | Portrait (4:5) |
| `images/services/03-architraves.jpg` | Service card 03 | 800 x 1000 | Portrait (4:5) |
| `images/services/04-wall-panelling.jpg` | Service card 04 | 800 x 1000 | Portrait (4:5) |
| `images/services/05-timber-battens.jpg` | Service card 05 | 800 x 1000 | Portrait (4:5) |
| `images/services/06-timber-feature-walls.jpg` | Service card 06 | 800 x 1000 | Portrait (4:5) |
| `images/services/07-finishing-carpentry.jpg` | Service card 07 | 800 x 1000 | Portrait (4:5) |
| `images/services/08-architectural-detailing.jpg` | Service card 08 | 800 x 1000 | Portrait (4:5) |
| `images/projects/01-oak-wall-panelling.jpg` | Featured project 01 (wide) | 1600 x 800 | Landscape |
| `images/projects/02-concealed-internal-doors.jpg` | Featured project 02 | 1000 x 800 | Landscape |
| `images/projects/03-skirtings-architraves.jpg` | Featured project 03 | 1000 x 800 | Landscape |
| `images/projects/04-spotted-gum-batten-wall.jpg` | Featured project 04 (wide) | 1600 x 800 | Landscape |

## Tips

- The hero photo also doubles as the social share image (Open Graph), so pick a strong one.
- The featured project labels (name and location) live in `index.html`. To rename a
  project, edit the `.n` and `.loc` text in the Projects section and rename the matching file.
- To add or remove a service card or project, copy one of the existing blocks in
  `index.html` and update the image path, label, and number.
- Logo: the mark on the page is embedded directly in `index.html`, so it always shows.
  `images/logo.png` is used for the browser favicon and as a backup asset.
