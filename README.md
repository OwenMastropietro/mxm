# Mixture Motor

A first website for an old name. One page, the family's own photographs, written as a birthday sketch so the domain has something on it while the real site gets decided.

The look follows the first draft already in this folder: paper, burnt orange, condensed type, a journal rather than a shop. The stock photos that draft used are gone. The machines in `assets/` are the issue.

## What's on the page

- A masthead with the Mixture Motor Co. badge
- The cafe racer as the front
- Six notes, one per machine, opened from the journal
- The birthday note, kept from the first draft

`assets/mxm-riviera.jpg` is the original, plate and all, and is not used on the page. `assets/mxm-riviera-road.jpg` is the same photograph with the plate removed, which is the one the site shows. The trunk photograph stays in the folder for a later note; it isn't on the page because the plate is readable in it.

## Run it

Open `index.html`, or from this folder:

```sh
python3 -m http.server 4173
```

Then visit http://localhost:4173.

## Change it

The whole site is `index.html` plus `assets/`. Drop a new photograph in `assets/`, point an `<img>` at it, and rewrite the few lines next to it. No build step, no accounts, no framework. When the domain moves, this folder is the site.
