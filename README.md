# Gigi Tachinardi — portfolio

Static site: `index.html` (all CSS/JS inline) + `img/` (stills, loops, logos). No build step.

## Preview locally
Open `index.html` in a browser.

## Publish (free)
Cloudflare Pages or Netlify: connect this repo, no build command, output directory `/` (root). Every push to `main` redeploys.

## Domain
Keep gigitachinardi.com on Cargo until the new site is ready. At launch, point the domain's DNS to the host (the host shows the exact records), then cancel Cargo.

## Before cancelling Cargo
Download originals of anything still hosted there (files.cargocollective.com / freight.cargo.site) and point them to `img/`.

## Versions
One commit per change; roll back by reverting a commit.
