# Portfolio repo

This repository is Raptor's public GitHub profile and portfolio.

- `README.md` is the profile shown on github.com/actualraptor. Keep it short: intro, portfolio link, featured project, one line per other project.
- `index.html` is the portfolio site, served by GitHub Pages at https://actualraptor.github.io/actualraptor/ from the `main` branch root. It is one self-contained file: CSS in the `<style>` block, no build step, no JavaScript needed.

## Adding or updating a project

1. In `index.html`, add an `<article class="card">` inside `<div class="cards">` in the `#work` section: a `chip` (Live game, Live app, Passion project...), an `<h3>` name, one sentence, two or three bullets, and a `foot` line with status or a public link.
2. Add the matching one-line entry to `README.md`.
3. Commit to `main` and push. Pages redeploys on its own.

Rexload is the featured case study (`#rexload` section, Problem / Approach / Outcome). Only replace it as the feature if Raptor says so.

## Voice and rules

- LinkedIn-style, first person, outcome-led: what was owned, designed, shipped. Short sentences.
- Never invent metrics, user numbers, job titles or employers. Use only facts Raptor gives or that the project itself shows.
- Fan projects built on other companies' games are "passion projects": describe them generically, do not name the game or link to them unless Raptor asks.
- No contact details, real name or email unless Raptor provides them for publication.
- Everything pushed here is public. Do not link to private Claude artifacts; say "available on request" instead.
- Keep the page's existing design tokens (the `:root` block) and layout; add content, do not restyle, unless asked.
