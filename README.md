# Blueberryjam — Landing Page

Landingspagina voor Blueberryjam: persoonlijke AI Governance praktijk. De funnel: **gratis Quickscan → Deepdive → 90 dagen uitvoering → Quarterly Governance Partnership**, met het Vibe Café als instapervaring.

## Stack

Eén zelfstandig `index.html` bestand — geen build step, geen dependencies. HTML + CSS + een paar regels vanilla JS voor scroll-animaties. Fonts via Google Fonts (Inter + Space Grotesk).

## Lokaal bekijken

```bash
open index.html
# of
python3 -m http.server 8000
```

## Deployen

Het bestand kan rechtstreeks op elke statische host (Netlify, Vercel, GitHub Pages, Cloudflare Pages).

## Aanpassen

- **CTA-links**: de knoppen "Start de scan" verwijzen nu naar een mailto. Vervang door de URL van de zelfscan-tool zodra die live is (zoek op `mailto:` in `index.html`).
- **Kleuren/branding**: alle design tokens staan bovenaan in de `:root` CSS-variabelen.
- **Copy-stijl**: ik-vorm, geen em-dashes.
