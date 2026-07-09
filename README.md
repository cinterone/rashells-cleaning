# Rashelle's Cleaning Service — Website

Single-file static site (`index.html`). No build step needed.

## Before deploying

1. **Contact form**: Sign up free at [formspree.io](https://formspree.io), create a form, and replace `YOUR_FORM_ID` in `index.html` with your form ID. Submissions will arrive in Rashelle's email inbox.
2. **Email link**: Replace `rashelle@example.com` (appears twice near the bottom of `index.html`) with her real email.

## Deploy to Vercel (easiest way — no terminal)

1. Go to [vercel.com](https://vercel.com) and sign up (free Hobby plan).
2. From the dashboard, drag and drop this `rashelles-cleaning` folder onto the "Deploy" area — or click **Add New → Project → Deploy without Git** if prompted.
3. Vercel gives you a URL like `rashelles-cleaning.vercel.app`.

## Deploy via CLI (alternative)

```bash
npm i -g vercel
cd rashelles-cleaning
vercel --prod
```

## Custom domain (optional)

Buy a domain (e.g., `rashellescleaning.com`) and add it in the Vercel project's **Settings → Domains**. Vercel handles HTTPS automatically.
