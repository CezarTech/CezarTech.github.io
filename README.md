# Cezar Morshid — Portfolio

A single-page portfolio site (HTML + CSS, no build step), ready for GitHub Pages.

## Files
- `index.html` — the whole website
- `assets/cezar.jpg` — profile photo
- `assets/favicon.png` — browser tab icon

## Publish free on GitHub Pages
1. Create a new **public** repository on GitHub named exactly `CezarTech.github.io`
   (your username + `.github.io`). This gives you the free address
   **https://cezartech.github.io**
2. Click **Add file → Upload files**, drag in `index.html`, `README.md` and the `assets` folder, then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. Wait 1–2 minutes and open https://cezartech.github.io

(If you use any other repository name, e.g. `portfolio`, the address becomes `https://cezartech.github.io/portfolio`.)

## Custom domain (optional)
Buy a domain (e.g. cezarmorshid.com), then in **Settings → Pages → Custom domain** enter it, and at your domain provider add:
- four `A` records for `@` → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- a `CNAME` record for `www` → `cezartech.github.io`
Then tick **Enforce HTTPS**.

## Editing
Open `index.html` in any text editor — every section is labelled with a comment (HERO, WORK, SERVICES, EXPERIENCE, SKILLS, CONTACT). To add a new app, copy one `<article class="card">…</article>` block and change the text and link.
