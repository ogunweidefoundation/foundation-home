# Leonard & Grace Ogunweide Foundation — Frontend

## Quick start
1. Download/clone this folder.
2. Open `index.html` in your browser to preview.
3. Replace placeholder images in `assets/img/` and logo in `assets/icons/logo.svg`.
4. Edit text directly in the HTML. Colors & spacing live in `assets/css/styles.css` (`:root` tokens).

## Deploy (Netlify)
- Create a Netlify account → "Add new site" → "Import from Git".
- Select your GitHub repo, accept defaults, and deploy.
- Add custom domain (from Namecheap/Google Domains) → enable HTTPS.

## Donations (Paystack)
- Get your Paystack **public key**.
- In `donate.html`: uncomment the Paystack script tag and the JS handler.
- Replace `PAYSTACK_PUBLIC_KEY` with your real key.
- Optional: on success, redirect to a `/thank-you.html` page.

## Forms (no backend)
- Newsletter form already supports Netlify Forms. In Netlify dashboard, enable Forms to start collecting submissions.

## Accessibility & performance
- Alt text included; semantic landmarks used.
- Images should be optimized (use 1600px wide hero, ~200–300KB).
