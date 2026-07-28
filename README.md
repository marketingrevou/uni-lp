# RevoU Landing Pages

Static landing pages, deployed on Vercel. No build step — files are served as-is
from the repo root, so each top-level folder maps directly to a URL path.

## Structure

```
binus-university/      -> /binus-university
├── index.html
└── images/
```

Each page folder is self-contained and holds its own `images/`. Asset paths
inside `index.html` are relative (`images/...`), so a folder can be renamed and
the URL changes with it — no edits to the HTML needed.

## Adding a page

1. Create a folder named after the desired URL path (e.g. `universitas-x/`).
2. Put `index.html` and an `images/` folder inside it.
3. Reference assets relatively: `<img src="images/hero.png">`.

## Deploy

Pushes to `main` deploy to production automatically. Other branches and pull
requests get preview URLs.

Vercel project settings: Framework Preset **Other**, no build command, output
directory **/** (repo root).

`vercel.json` sets `cleanUrls` (so `/binus-university` works without a trailing
slash or `.html`) and redirects the bare domain `/` to `/binus-university`.
Remove that redirect once there is a real homepage.
