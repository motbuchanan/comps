# Michael DeLisi portfolio site - ROADMAP

Last updated: 2026-10-07
Current version: draft v0.1 (first take, built from Instagram screenshots)

## What this is
Single-page portfolio for Michael DeLisi (surface texturing / look development, SCAD Visual Effects 2022).
One index.html plus image files, all at the repo root. No build step. Route B (free static hosting, dedicated repo).

## Files
- index.html: the whole site (markup, styles, script)
- md-*.jpg: 10 work images and 6 archive thumbnails, all cropped from Instagram screenshots (stand-ins)
- .nojekyll: empty, keeps GitHub Pages from running Jekyll
- ROADMAP.md: this file

## Shipped in v0.1
- Header with rebuilt M/D monogram (SVG stand-in for his real logo file)
- Hero name with the slash, role line, demo reel stand-in (still image with slow push, opens a video frame)
- Selected Work: Flayed Beast (slash wipe, clay vs final), Spined Reptile (5 views), Goblin Bust, Mech (2 views), Dive Bomber
- Breakdowns: Studio 1 and Studio 2 title cards, both open the video frame
- Earlier Studies: 6 thumbnails
- About, Toolset, Contact
- Lightbox on every image
- Draft notes: amber text and dashed underlines mark everything unconfirmed; "notes" button hides them

## Stand-ins to replace
- All images: full-resolution originals from Michael
- Reel and both breakdowns: Vimeo or YouTube links (frame is ready)
- Slash wipe Clay side: real untextured render of the beast (currently a grey filter)
- Monogram: his real logo file
- Archive thumbnails: soft, upscaled from the profile grid

## To confirm with Michael
- Which role leads: texturing / lookdev, or sculpting
- Piece titles (all five are working titles)
- Mentor credit spelling on the beast (read as "Solene Chan-Lam")
- Model credits for Goblin Bust, Mech, Dive Bomber
- CGMA course line on the bust
- Software per piece, and the Toolset list (only ZBrush confirmed)
- Studio 1 breakdown run time (Studio 2 is 0:42)
- Email address (read off his reel card), resume, LinkedIn, ArtStation links
- "Open to work" line and the bio (he should rewrite it in his own words)
- What is cleared to show
- Old Wix site screenshots, domain status for michaeldelisiart.com, two sites he likes

## Before going public
- Remove the dev badge block and its .dev / .toast CSS (marked in index.html)
- Remove every .note line and every tbc class
- Add Open Graph tags with a chosen share image
- Keep a backup copy of the final index.html outside the repo
