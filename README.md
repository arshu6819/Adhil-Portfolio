# Adhil Abdul Jaleel — Portfolio Site

A single-page portfolio site, ready to host for free on **GitHub Pages**.

## What's inside
- `index.html` — the whole site (no build step, no dependencies to install)
- `images/` — all photos, already resized and compressed for the web

## Deploy on GitHub Pages (free)
1. Create a new repository on GitHub (e.g. `adhil-portfolio`).
2. Upload `index.html` and the `images/` folder to the repo (drag-and-drop on
   github.com works, or `git add . && git commit -m "portfolio" && git push`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. GitHub gives you a live URL within a minute or two, usually:
   `https://<your-username>.github.io/<repo-name>/`

## Before you publish
- Swap the placeholder email in the "Email Adhil" button
  (`mailto:youremail@example.com` near the bottom of `index.html`) for a real
  contact address — none was in the source portfolio, so a placeholder was
  used.
- Everything else (bio, experience, dishes, references) is pulled directly
  from the portfolio PDF you shared.

## Editing later
It's plain HTML/CSS — open `index.html` in any text editor. Section
comments aren't included, but each `<section class="course">` block maps to
one part of the site (About, Experience, Chef's Story, Portfolio gallery,
References, Contact).
