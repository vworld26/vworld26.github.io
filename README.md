# vernonsteward.com

Personal website for Vernon Steward — operator, builder, CEO of Prota Studios.

## Stack

Plain HTML and CSS in a single file (`index.html`). No build step, no framework, no dependencies.

## Local preview

Open `index.html` directly in a browser, or run a tiny local web server from this folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy

Hosted on GitHub Pages, pointed at the custom domain `vernonsteward.com`.

## Edit

The whole site lives in `index.html`. Content sits inside `<section>` tags in `<main>`; styling lives in the `<style>` block in `<head>`. Colors and spacing are defined as CSS variables in `:root` near the top of the `<style>` block — change one value and it cascades everywhere.
