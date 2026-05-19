# Mohammad Abujoudeh Portfolio

A minimal dark portfolio for Mohammad Ahmad Abujoudeh, built as a single-file GitHub Pages site.

## Live Portfolio

After publishing `gh-pages`, the site will be available at:

https://muhabujoude.github.io/

## What It Does

- Fetches GitHub profile data from `https://api.github.com/users/muhabujoude`
- Fetches repositories from `https://api.github.com/users/muhabujoude/repos?per_page=100&type=all&sort=updated`
- Fetches recent public activity from `https://api.github.com/users/muhabujoude/events/public?per_page=100`
- Combines public repositories and recent activity repositories without duplicates
- Sorts GitHub work by stars, then recent updates
- Includes professional profile details and featured project summaries from Mohammad's Toptal profile
- Uses vanilla HTML, CSS, and JavaScript only

## Design

- Dark background: `#0E0E0E` and `#111111`
- Gold accent: `#B8935A`
- Light text: `#F9F7F3`
- Typography: Cormorant Garamond and DM Sans
- Minimal layout with thin dividers and generous whitespace

## Edit Later

Update these placeholders in `index.html` when ready:

- Contact email: `hello@mohammadabujoudeh.dev`
- LinkedIn URL: `https://www.linkedin.com/in/mohammad-abujoudeh/`
- Fallback bio under the hero name

## Deploy

```bash
git remote add user-site https://github.com/muhabujoude/muhabujoude.github.io.git
git push -u user-site HEAD:main
```
