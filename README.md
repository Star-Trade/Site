# Star Trade — Investor & Marketing Site

Static, zero-dependency site (`index.html` + `styles.css` + `script.js`). No
build step, nothing to install.

## Preview locally

```powershell
python -m http.server 8080
# open http://localhost:8080
```

(Or just double-click `index.html`.)

## Before sending it to investors

Update the contact email — search `index.html` for `hello@startrade.app`
(3 occurrences) and replace with your real inbox.

## Host it (pick one)

- **Netlify Drop** (fastest): drag this folder onto app.netlify.com/drop.
  Set a custom subdomain under Site settings.
- **Vercel**: `vercel deploy` from this folder, or import the repo.
- **GitHub Pages**: push this folder as its own repo, then
  Settings → Pages → Deploy from branch (main, root).

All three are free for a static site. Add your custom domain whenever ready.
