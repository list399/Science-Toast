# Science Toast

A simple link-sharing site. Posts are managed via a Google Sheet — no code changes needed to add new content.

## How to add posts

1. Open the Google Sheet
2. Add a new row with three columns:
   - `url` — the full link including https://
   - `title` — the text that will appear as the clickable link
   - `blurb` — a short description of the content
3. The site updates automatically on the next page load

## How the site works

`index.html` fetches the published Google Sheet as a CSV on every page load and renders the rows as a list of posts. There is no database or backend.

## Files

- `index.html` — the entire site

## Hosted on

GitHub Pages
