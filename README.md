# MuViSeg project page

Project page for **MuViSeg: Multi-View Segment Correspondences from Dense Geometry Priors** (ACCV 2026).

Static site, no build step. Served by GitHub Pages from the repository root.

```
index.html              the whole page (markup, styles and script in one file)
static/images/          teaser, architecture, result figures
static/videos/          joint-window demos on the robot capture (mp4 + poster frames)
static/paper.pdf        the paper
.nojekyll               tells GitHub Pages to serve files as-is, without Jekyll
```

## Before going public

- Replace `REPLACE_WITH_SITE_URL` in the `<head>` of `index.html` (3 places) with the live site
  address, so link previews work on X, Telegram and Slack.
- Fill in the arXiv and Code buttons in the hero — they currently point at `#`.
- Replace `static/paper.pdf` with the camera-ready version.
