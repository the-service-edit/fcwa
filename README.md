# FCWA site images

Drop your photos into this folder using the exact filenames below. The site reads
them automatically. Until a file exists, that slot shows a warm placeholder panel
with batten lines, so the page never looks broken while you are still loading photos.

Format: JPG (or WebP if you prefer, just change the extension in index.html).
Keep each file under roughly 300 to 500 KB for fast loading. The site crops to fit,
so the focal point should sit near the centre.

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
| `images/projects/01-oak-wall-panelling.jpg` | Featured project 01 AFTER (wide) | 1600 x 800 | Landscape |
| `images/projects/02-concealed-internal-doors.jpg` | Featured project 02 AFTER | 1000 x 800 | Landscape |
| `images/projects/03-skirtings-architraves.jpg` | Featured project 03 AFTER | 1000 x 800 | Landscape |
| `images/projects/04-spotted-gum-batten-wall.jpg` | Featured project 04 AFTER (wide) | 1600 x 800 | Landscape |

## Before / after (the strongest proof you have)

Each featured project can show a BEFORE photo on hover (and on tap, on phones).
Add a matching file with `-before` on the end of the name and it switches on
automatically. Leave it out and the project just shows the finished shot, no empty
toggle appears.

| File | Used for |
|------|----------|
| `images/projects/01-oak-wall-panelling-before.jpg` | Project 01 BEFORE |
| `images/projects/02-concealed-internal-doors-before.jpg` | Project 02 BEFORE |
| `images/projects/03-skirtings-architraves-before.jpg` | Project 03 BEFORE |
| `images/projects/04-spotted-gum-batten-wall-before.jpg` | Project 04 BEFORE |

### Shoot brief for FCWA (the habit that makes this work)

The before/after only lands if the two shots match. Make this a standing routine on site:

1. BEFORE: shoot the raw space before second fix begins. Note the exact spot you stood,
   roughly eye height, holding the phone level. You cannot go back and get this later.
2. DURING: a few progress shots (battens going up, a door being hung). Great for Instagram.
3. AFTER: shoot the finished work from the SAME position, same height, same framing as the before.

Matched framing is what makes the pair convincing. Same spot, same height, same angle.

## Tips

- The hero photo also doubles as the social share image (Open Graph), so pick a strong one.
- Project names and locations live in the Projects section of `index.html`. To rename
  a project, edit the `.n` and `.loc` text and rename the matching files (after and before).
- Logo: embedded directly in `index.html`, so it always shows. `images/logo.png` is the favicon.
