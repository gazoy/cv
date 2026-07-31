# Gareth Oyston — CV

A single-page animated CV: dark, terminal-inspired design with an Elliott
Wave hero animation and a scrolling skills ticker.

## Host it for free on GitHub Pages

1. Create a new GitHub repository (public), e.g. `gareth-oyston-cv`.
2. Upload `index.html` to the root of that repo (drag-and-drop on
   github.com works, or `git add / commit / push`).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a
   branch**, pick branch `main` and folder `/ (root)`, then **Save**.
5. Wait ~1 minute, then your CV is live at:
   `https://<your-github-username>.github.io/gareth-oyston-cv/`

## Things to check before you publish

- `(in progress)` next to the PhD, in the Focus Areas section — update
  if you have a target completion date.

## Editing content

Everything is in one file, `index.html`:
- Copy lives directly in the HTML body, organised by section
  (Hero, Profile, Focus Areas, Education, Skills ticker, Contact).
- Skills shown in the bottom ticker are set in the `skills` array
  near the bottom of the `<script>` block — add or remove items
  there.
- Colors, fonts, and spacing are all defined as CSS variables at the
  top of the `<style>` block under `:root`.

No build step, no dependencies to install — it's plain HTML/CSS/JS.
