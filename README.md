# Nate Price — Founder HQ prototype

Static multi-page site for iamnateprice.com (hybrid: Squarespace domain + custom host).

## Local
```bash
python3 -m http.server 8765
```
Open http://127.0.0.1:8765/

## Deploy (Vercel)
From this folder:
```bash
npx vercel --yes
```
Then attach custom domain `iamnateprice.com` after Nate points Squarespace DNS.

## Pages
- `index.html` — locked motion hero
- `about.html` — Navy / Maine / EnkiLabs
- `work.html` — Gambit + SteadyPulse
- `contact.html` — FormSubmit + mailto + LinkedIn
