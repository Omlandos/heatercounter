# heatercounter.com

Marketing site and legal pages for **Heater** — a blackjack card counting app for iOS and Android.

This is a static HTML site deployed on Vercel.

## Pages

- `/` — Landing page
- `/privacy` — Privacy policy
- `/terms` — Terms of service
- `/support` — Support and contact

## Local development

No build step. Open the HTML files directly in a browser, or run a simple local server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Auto-deployed via Vercel on every push to `main`. No configuration needed — Vercel detects it as a static site.

## Updating the legal pages

These pages must stay accurate and up to date. When changing the app's behavior in any way that affects user data or terms, update both pages and bump the "Last updated" date at the bottom.

## Contact

Heater — a card counting tool by Olav.
