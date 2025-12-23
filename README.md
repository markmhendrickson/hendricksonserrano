# hendricksonserrano.com

General purpose repository for hendricksonserrano.com domain and subdomains.

## Structure

- `mark/` - Mark subdomain site (mark.hendricksonserrano.com)

## Deployment

The mark subdomain is automatically deployed via GitHub Actions when files in `mark/` are updated.

## Setup

1. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: GitHub Actions
   - Custom domain: `mark.hendricksonserrano.com`
   - Enable "Enforce HTTPS"

2. Configure DNS:
   - Add A records for `mark.hendricksonserrano.com` pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Or add CNAME: `mark.hendricksonserrano.com` → `markmhendrickson.github.io`

