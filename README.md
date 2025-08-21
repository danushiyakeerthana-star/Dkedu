# DKEDU Static Site

A fast, single‑page static website for DKEDU (`index.html` + `styles.css`).

## 🚀 Deploy – GitHub Pages (free URL)
1. Create a new repo on GitHub, e.g. `dkedu-site`.
2. Upload these files (`index.html`, `styles.css`, `.nojekyll`, `README.md`).
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch** → Branch: **main** → Folder: **/** (root).
5. Wait a minute. Your site will be live at: `https://<your-username>.github.io/dkedu-site/`.

## 🚀 Deploy – Vercel (free subdomain)
1. Go to **vercel.com** → New Project → Import from GitHub (select this repo).
2. Framework preset: **Other** (static).
3. Build & Output: *leave defaults* (Vercel detects `index.html`).
4. Deploy. You’ll get `https://<project-name>.vercel.app` (SSL included).

## ✅ Optional: Custom Domain (Freenom) → Vercel
- Add DNS:
  - **A** for apex: `76.76.21.21`
  - **CNAME** for `www`: `cname.vercel-dns.com`
- In Vercel → Project → **Settings → Domains** → Add your domain and verify.

---

### Local preview
Just open `index.html` in a browser (no build needed).

### Notes
- `.nojekyll` ensures GitHub Pages serves files without Jekyll processing.
- `vercel.json` is included for clean static hosting (optional).
