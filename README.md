# Jaeden Hernan — IT Portfolio

A single-page, plain HTML + CSS portfolio. No build step, no JavaScript, no dependencies.

Files: `index.html`, `styles.css`.

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000   # then visit http://localhost:8000
```

## Before publishing: fill the placeholders

Search `index.html` for `[` and `your-` and replace:

- Contact: email, GitHub and LinkedIn links
- Experience: NewShine start year, part-time employer, dates and a real accomplishment
- Education: expected graduation date, relevant courses and certifications
- Skills: remove anything you can't speak to in an interview

## Deploy

All options are free and serve the folder as-is.

**GitHub Pages**
1. Push this folder to a GitHub repo.
2. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Site appears at `https://<username>.github.io/<repo>/`.

**Netlify** — drag the folder onto app.netlify.com/drop, or connect the repo with no build command and publish directory `.`.

**Cloudflare Pages** — connect the repo, framework preset "None", build command empty, output directory `/`.

**Any web host** — upload `index.html` and `styles.css` to the web root.

## Accessibility notes

Semantic landmarks, skip link, visible focus styles, one `h1` with ordered headings, AA-contrast colours, 44px tap targets, and `prefers-reduced-motion` respected.
