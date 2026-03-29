# AI × GRC × FSI Signals — Website

A curated newsletter website for governance, risk, and compliance professionals navigating AI adoption in financial services.

## Structure

```
├── index.html          # Homepage with latest issue
├── styles.css          # Dark mode professional theme
├── script.js           # Smooth scroll, nav highlighting
├── issues/             # Individual issue pages
│   ├── 2026-03-31.html
│   ├── 2026-03-26.html
│   └── ...
├── archive.html        # All issues list
├── about.html          # About page
├── feed.xml            # RSS feed
└── README.md           # This file
```

## GitHub Pages Setup

1. Push this repo to `https://github.com/kdeath83/AI-GRC-FSI-Signals-`
2. Go to **Settings → Pages**
3. Select **Deploy from a branch**
4. Choose **main** branch and **/(root)** folder
5. Your site will be at: `https://kdeath83.github.io/AI-GRC-FSI-Signals-`

## Custom Domain (Optional)

To use a custom domain:

1. Add a file named `CNAME` containing your domain:
   ```
   aixgrc.krishde.com
   ```
2. Configure DNS with your provider (A records to GitHub IPs)
3. Enable HTTPS in GitHub Pages settings

## Adding New Issues

1. Copy `template.html` to `issues/YYYY-MM-DD.html`
2. Update issue number, date, title, and signals
3. Add to `index.html` hero section and archive list
4. Update `feed.xml` with new entry

## Newsletter Integration — Beehiiv

This site uses **Beehiiv** for email subscriptions (2,500 subscribers free).

### Quick Setup

1. Sign up at https://beehiiv.com
2. Get your embed code: Settings → Integrations → API & Embeds
3. Replace `YOUR_PUBLICATION_ID` in `index.html` with your actual embed URL
4. Deploy: `git push`

See `BEEHIIV-SETUP.md` for detailed instructions.

### Why Beehiiv?

- Free up to 2,500 subscribers
- Your own domain and branding
- Deep analytics + referral programs
- 100% revenue if you go paid (no 10% cut like Substack)
- Full API access for custom integrations
- Export your list anytime (you own your audience)

## License

© 2026 Krish De. All rights reserved.
