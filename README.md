# noas-world-feed

Static hosting for a private-use bedtime-story podcast feed.

- `feed.xml` — iTunes RSS, served via GitHub Pages, regenerated on every
  publish by the [noas-world](https://github.com/daldaman/noas-world)
  pipeline. Subscribe by URL in Apple Podcasts; the feed is unlisted, not
  submitted to any directory.
- `episodes.json` — episode manifest (source of truth for feed regeneration).
- `artwork.png` — channel artwork (placeholder gradient; replace anytime).
- Episode audio lives in this repo's **Releases**, one release per episode,
  tagged `ep-<content-hash>`.

All four files are written by the pipeline via the GitHub API — nothing here
is edited by hand except this README and the artwork.
