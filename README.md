# Oasis Custom Pools

Website for Oasis Custom Pools — Murfreesboro, TN.

## Publishing via GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `main` branch, `/ (root)` folder → Save
4. Your site will be live at `https://yourusername.github.io/repo-name/`

## Custom Domain (oasispoolstn.com)

The `CNAME` file is already configured for `oasispoolstn.com`.

After enabling GitHub Pages, go to your domain registrar and add these DNS records:

| Type  | Host | Value               |
|-------|------|---------------------|
| A     | @    | 185.199.108.153     |
| A     | @    | 185.199.109.153     |
| A     | @    | 185.199.110.153     |
| A     | @    | 185.199.111.153     |
| CNAME | www  | yourusername.github.io |

DNS changes take 10–30 minutes. GitHub Pages provides a free SSL certificate automatically.

## Files

- `index.html` — the complete website (single file, self-contained)
- `CNAME` — custom domain configuration for GitHub Pages
