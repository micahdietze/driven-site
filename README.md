# DRIVEN Detailers — Website

Mobile car detailing website for North County San Diego.

## Structure

```
driven-detailers/
├── index.html           # Main homepage
├── booking.html         # Dedicated booking page (multi-step flow)
├── driven_logo.png      # Brand logo
├── site.webmanifest     # PWA manifest
├── favicon-*.png        # Favicon files
├── apple-touch-icon.png
├── android-chrome-*.png
└── photos/              # Before/after gallery images
    ├── slider-before.PNG
    ├── slider-after.PNG
    ├── before-interior.PNG
    ├── after-interior.PNG
    ├── detail-before.PNG
    ├── detail-after.PNG
    ├── ext-before.PNG
    ├── ext-after.PNG
    └── (extra before/afters for future use)
```

## Deploying via Vercel

1. Push this folder to GitHub
2. Go to vercel.com → Add New Project → Import from GitHub
3. Select this repo, deploy with default settings (no framework needed)
4. Your site is live at a `.vercel.app` URL

To connect a custom domain: Project Settings → Domains → Add your domain.

## Instagram Widget (not yet active)

To add a live Instagram feed:
1. Go to [lightwidget.com](https://lightwidget.com)
2. Sign in with @driven.detailers
3. Create a Responsive Grid widget
4. In `index.html`, find the comment `PASTE INSTAGRAM WIDGET CODE HERE` and replace the placeholder div with your embed code

## Formspree (booking form)

Both the booking flow on `booking.html` submits to Formspree endpoint `mykappoo`.
Submissions arrive in your Formspree dashboard and are forwarded to your email.
