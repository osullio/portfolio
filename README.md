# portfolio

Portfolio of my projects. Live at **https://osullio.github.io/portfolio/**

Plain HTML/CSS, no build step.

```
index.html              Home: intro, experience, project cards, other work, skills, about
css/style.css           All styling (automatic light/dark mode)
projects/
  cadence-internship.html Cadence internship (general terms only)
  computer-vision.html  Abandoned & Removed Object Detection
  earth-lunar.html      Earth–Moon Rover Communication
  arduino-pong.html     Gyroscopic Arduino Pong (YouTube embed)
  _template.html        Copy this for projects without public code
assets/
  img/                  Thumbnails and screenshots
```

## Publishing
Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.

## Adding a project
1. Copy `projects/_template.html` and fill it in.
2. Copy a card in `index.html` and point its "Read more" button at the new page.
3. Search the files for `EDIT` and `[` to find any placeholders you haven't filled in yet.
