# Serena Lee Photography

One-page portfolio site for freelance photographer Serena Lee. Plain HTML and CSS, no build step.

## Deploy on Vercel

1. Import this repository at https://vercel.com/new.
2. Leave the framework preset as **Other**. No build command, no output directory.
3. Deploy. Vercel serves `index.html` from the repo root.

CLI alternative: `npx vercel --prod`

## Local preview

Open `index.html` in a browser, or run `npx serve .`

## Editing

- Replace the placeholder email (`hello@serenalee.com`) in the contact section.
- Photos are inline in `index.html`. To add one, replace a `.ph` placeholder `<div>` with an `<img class="photo">`. Put image files in an `images/` folder and reference them by path.
