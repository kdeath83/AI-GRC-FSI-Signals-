# Beehiiv Setup Instructions

## Step 1: Create Your Beehiiv Account

1. Go to https://beehiiv.com
2. Sign up with your email (krishde@gmail.com)
3. Create a new publication called **"AI × GRC × FSI Signals"**
4. Choose the **Launch** (free) plan — you get 2,500 subscribers free

## Step 2: Get Your Embed Code

1. In Beehiiv dashboard, go to **Settings** → **Integrations** → **API & Embeds**
2. Click **"Create Embed"**
3. Choose **"Slim"** style (matches your clean design)
4. Copy the iframe code
5. It will look like:
   ```html
   <iframe src="https://embeds.beehiiv.com/a1b2c3d4-5678-90ab-cdef-example11111?slim=true" ...
   ```

## Step 3: Update Your Website

Replace this line in `index.html`:
```html
<iframe src="https://embeds.beehiiv.com/YOUR_PUBLICATION_ID?slim=true" ...
```

With your actual embed URL from Beehiiv.

## Step 4: Deploy

```bash
cd ai-grc-fsi-signals
git add .
git commit -m "Add Beehiiv subscribe embed"
git push
```

## Optional: Custom Domain

In Beehiiv Settings → **Domains**:
1. Add custom domain: `newsletter.krishde.com` (or whatever you want)
2. Follow DNS instructions
3. Your subscribe page becomes: `newsletter.krishde.com/subscribe`

## Features You'll Get

- **Free up to 2,500 subscribers**
- **Referral program** (built-in)
- **Deep analytics** (open rates, click maps)
- **API access** (for future integrations)
- **Export anytime** (you own your list)
- **GDPR compliant** (handles unsubscribes, etc.)

## Need Help?

Beehiiv docs: https://docs.beehiiv.com
Email me if stuck!
