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
| `images/services/01-second-fix-finishing.jpg` | Service card 01 | 800 x 1000 | Portrait (4:5) |
| `images/services/02-wall-panelling.jpg` | Service card 02 | 800 x 1000 | Portrait (4:5) |
| `images/services/03-timber-feature-walls.jpg` | Service card 03 | 800 x 1000 | Portrait (4:5) |
| `images/services/04-decking.jpg` | Service card 04 | 800 x 1000 | Portrait (4:5) |
| `images/services/05-timber-cladding.jpg` | Service card 05 | 800 x 1000 | Portrait (4:5) |
| `images/services/06-custom-carpentry.jpg` | Service card 06 | 800 x 1000 | Portrait (4:5) |
| `images/services/07-new-builds-renovations.jpg` | Service card 07 | 800 x 1000 | Portrait (4:5) |
| `images/services/08-builder-subcontract.jpg` | Service card 08 | 800 x 1000 | Portrait (4:5) |
| `images/projects/project-01-after.jpg` | Project 01 AFTER | 1200 x 1200 | Square |
| `images/projects/project-02-after.jpg` | Project 02 AFTER | 1200 x 1200 | Square |
| `images/projects/project-03-after.jpg` | Project 03 AFTER | 1200 x 1200 | Square |
| `images/projects/project-04-after.jpg` | Project 04 AFTER | 1200 x 1200 | Square |

## Before / after (the strongest proof you have)

Each featured project can show a BEFORE photo on hover (and on tap, on phones).
Each project uses a matched pair: `<name>-after.jpg` and `<name>-before.jpg`.
Add the `-before` file and the reveal switches on automatically. Leave it out and the project just shows the finished shot, no empty
toggle appears.

| File | Used for |
|------|----------|
| `images/projects/project-01-before.jpg` | Project 01 BEFORE |
| `images/projects/project-02-before.jpg` | Project 02 BEFORE |
| `images/projects/project-03-before.jpg` | Project 03 BEFORE |
| `images/projects/project-04-before.jpg` | Project 04 BEFORE |


### What each project slot is, right now

The image filenames are deliberately generic so you can rename projects without ever
renaming photos. The current titles are:

- project-01 = Decking & Cladding, Mosman Park
- project-02 = Spotted Gum Deck
- project-03 = Timber Framing & Curved Staircase, Maylands
- project-04 = Cedar-lined Eaves

### Shoot brief for FCWA (the habit that makes this work)

The before/after only lands if the two shots match. Make this a standing routine on site:

1. BEFORE: shoot the raw space before work begins. Note the exact spot you stood,
   roughly eye height, holding the phone level. You cannot go back and get this later.
2. DURING: a few progress shots. Great for Instagram.
3. AFTER: shoot the finished work from the SAME position, same height, same framing as the before.

Matched framing is what makes the pair convincing. Same spot, same height, same angle.

## Tips

- The hero photo also doubles as the social share image (Open Graph), so pick a strong one.
- Service and project names live in `index.html`. To rename one, edit the label / `.n`
  and `.loc` text and rename the matching image files (after and before).
- Logo: embedded directly in `index.html`, so it always shows. `images/logo.png` is the favicon.
