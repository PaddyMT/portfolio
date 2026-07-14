# Pradyumna Acharya — Portfolio

A single, self-contained `index.html` (no build step, no dependencies). Fonts load from
Google Fonts; everything else is inline. Works offline except for the webfonts.

## Preview locally
Just double-click `index.html` — it opens in your browser. That's it.

## Host it for free (pick one)

### Option A — Netlify Drop (fastest, ~30 seconds, no account-git needed)
1. Go to https://app.netlify.com/drop
2. Drag the whole `portfolio` folder onto the page.
3. You instantly get a live URL like `https://your-name.netlify.app`.
4. (Optional) In Site settings → rename the site, or add a custom domain for free.

### Option B — GitHub Pages (best for a permanent / custom-domain setup)
1. Create a new **public** repo, e.g. `pradyumna-portfolio` (or `pradyumnaacharya.github.io`).
2. Upload `index.html` (and this README) to it.
3. Repo → **Settings → Pages** → Source: `main` branch, `/root` → Save.
4. Live in ~1 min at `https://<username>.github.io/pradyumna-portfolio/`.

### Option C — Vercel or Cloudflare Pages
Import the repo (or drag the folder) at https://vercel.com or https://pages.cloudflare.com —
both are free for static sites and give instant HTTPS.

## Custom domain (optional)
Any of the above supports a free custom domain. Nice options: `pradyumna.dev`,
`pradyumnaacharya.com`, or a subdomain like `me.milago.ai`. Add the domain in the host's
dashboard and point a CNAME/A record at it — the host shows the exact value.

## Customizing
Open `index.html` and edit the text directly. Common tweaks:
- **Accent colour** — change `--accent` / `--accent-2` in the `:root` block near the top.
- **Add a real photo** — replace the `.pcard-mono` "PA" block in the hero (search for
  `pcard-mono`) with `<img src="me.jpg" alt="Pradyumna Acharya" style="width:100%;border-radius:14px" />`
  and drop `me.jpg` in this folder.
- **Content** — every section (About, Selected Work, Career, Capabilities, Contact) is plain
  HTML with clear comments like `<!-- ===== WORK ===== -->`.

## Get it featured
Once it's live, you can submit the URL to showcases like https://www.wallofportfolios.in
(the site you referenced) or https://www.awwwards.com.
