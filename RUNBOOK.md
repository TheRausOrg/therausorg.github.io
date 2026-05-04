# RUNBOOK – Main site

## Enable GitHub Pages
1. GitHub → repo Settings → Pages
2. Build & deployment: Deploy from branch → `main` / root

## Custom domain
- Set custom domain to `theraus.org`
- Enable HTTPS when available

## DNS notes
- `theraus.org` uses A/ALIAS/ANAME records (depends on DNS provider)
- `www` uses a CNAME to the GitHub Pages hostname
