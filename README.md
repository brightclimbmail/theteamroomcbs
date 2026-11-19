# The Team Room | Custom Bow Shop (concept site)

Mockup website for The Team Room CBS. Static HTML, no build step.

## Files
- `index.html` — the whole site (styles and scripts included)
- `assets/logo.png` — TTR logo, white on transparent

## Publish free on GitHub Pages
1. Sign in at github.com and click **New repository**.
2. Name it `theteamroomcbs`, set it to **Public**, click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` and the `assets` folder, then click **Commit changes**.
4. Go to **Settings > Pages**. Under **Branch**, pick `main` and `/ (root)`, then **Save**.
5. Wait 1–2 minutes. The site is live at `https://YOUR-USERNAME.github.io/theteamroomcbs/`.

## Point theteamroomcbs.com at it later
1. In the repo: **Settings > Pages > Custom domain**, enter `theteamroomcbs.com`, **Save**.
2. In Namecheap: **Domain List > Manage > Advanced DNS**, add:
   - 4 `A` records, host `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - 1 `CNAME` record, host `www`, value `YOUR-USERNAME.github.io`
3. Back in GitHub Pages, tick **Enforce HTTPS** once it becomes available.

## Placeholders to fill in
Address, hours, phone, the email address, the payment link on "Join the Season Pass", and the Google reviews block.
Photos are free Unsplash images loaded from Unsplash; swap in the shop's own photos when available.

