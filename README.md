# Kalkido Website

Landing page for [kalkido.app](https://kalkido.app) — the ad-free math practice app for kids (K–5).

## Structure

```
├── index.html      # Landing page (coming soon → full site post-launch)
├── README.md
├── LICENSE
└── .gitignore
```

## Deployment

Static HTML — deploy to any static hosting:

- **Namecheap Static Hosting** (included with domain)
- **GitHub Pages** (free, enable in repo Settings → Pages → main branch)
- **Cloudflare Pages** (free, auto-deploys from GitHub)
- **Netlify** (free tier)

### GitHub Pages (quickest)

1. Go to repo Settings → Pages
2. Source: Deploy from branch → `main` → `/ (root)`
3. Set custom domain: `kalkido.app`
4. Add DNS records in Namecheap:
   - `A` record → `185.199.108.153` (and .109, .110, .111)
   - `CNAME` for `www` → `kalkido.github.io`

## Roadmap

- [x] Coming soon page with email capture
- [ ] Connect email form to Mailchimp / ConvertKit
- [ ] Post-launch: full landing page with App Store & Play Store links
- [ ] Screenshots, feature showcase, pricing section
- [ ] Blog (optional, for SEO / content marketing)

## License

Proprietary — All rights reserved. See [LICENSE](LICENSE).
