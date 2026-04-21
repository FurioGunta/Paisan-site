# Paisan Purchasing Group — website

Static single-page site built from the Paisan board deck.

## Files

- `index.html` — all page content
- `styles.css` — styling (Fraunces + Inter from Google Fonts)
- `vercel.json` — Vercel config (clean URLs)

## Run locally

Any static server works. Two easy options:

```bash
# Python
python3 -m http.server 5173

# Node
npx serve .
```

Then open http://localhost:5173

## Deploy to Vercel

**Easiest:** go to https://vercel.com/new, drag this folder onto the page.

**CLI:**
```bash
npm i -g vercel
vercel           # preview
vercel --prod    # production
```

## Things to update before going live

- Replace the contact email `hello@paisangroup.com` in `index.html` with a real inbox.
- Set up a real form backend (Formspree, Resend, or Vercel's serverless functions) — the current form opens the user's mail client as a fallback.
- Add favicon + OG image if desired.
