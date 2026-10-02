# MostakimRoshid.com

Personal site: a single static `index.html` served by GitHub Pages from `main` on the custom domain in `CNAME`. Images live in `images/`; favicons sit at the repo root.

## Workflow

- The owner wants every change shipped to `main` without asking first.
- For each change: commit on a branch, push, open a pull request, then squash-merge it into `main` right away.
- After merging, the live site updates within a few minutes.
