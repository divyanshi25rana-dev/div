# Divyanshi Rana — Portfolio Site

A minimalist, one-page portfolio built from scratch: plain HTML, CSS and a
touch of JS. No build step, no dependencies to install — just static files,
ready for GitHub Pages.

## What's inside
```
index.html      the whole page
css/style.css   design system (colors, type, layout)
js/script.js    mobile nav toggle + gentle scroll reveal
```

## Publish it on GitHub Pages (5 minutes)

1. Create a new repository on GitHub, e.g. `divyanshi-rana.github.io`
   (using your GitHub username in that exact form gives you the shortest
   URL) — or any repo name you like, e.g. `portfolio`.
2. Unzip this folder and push its contents to the repository:
   ```bash
   cd path/to/unzipped-folder
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub: go to **Settings → Pages**, set **Source** to
   `Deploy from a branch`, branch `main`, folder `/ (root)`, then **Save**.
4. Your site will be live in a minute or two at:
   - `https://<your-username>.github.io/` (if the repo is named
     `<your-username>.github.io`), or
   - `https://<your-username>.github.io/<repo-name>/` otherwise.

## Editing the content
Everything is in `index.html`, in plain sections (`#about`, `#research`,
`#experience`, etc.) — just edit the text between the tags. Colors and
fonts are controlled from the top of `css/style.css` under `:root`.

## A note on the References section
The site currently publishes your referees' names, affiliations and email
addresses. Since this will be a public page, you may want to double check
with Dr. Kumar and Dr. Hassan that they're comfortable being listed
publicly (rather than just on a CV you send privately), or swap that
section for "References available on request."
