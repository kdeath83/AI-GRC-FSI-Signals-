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

## Newsletter Integration

The subscribe form uses Buttondown as an example. Replace with:
- **Buttondown:** `https://buttondown.email/api/emails/embed-subscribe/YOUR_NEWSLETTER`
- **Substack:** `https://yourname.substack.com/subscribe`
- **ConvertKit:** Your form action URL
- **Custom:** Your own backend

## License

© 2026 Krish De. All rights reserved.
