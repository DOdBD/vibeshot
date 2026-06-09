# BlueBerryJam — Landing Page

Landingspagina voor BlueBerryJam: persoonlijke AI Governance praktijk. De funnel: **gratis Quickscan → Deepdive → 90 dagen uitvoering → Quarterly Governance Partnership**, met het Vibe Café als instapervaring.

Visueel gebouwd op het **BlueBerryJam design system** (Claude Design handoff bundle): navy `#263450` + jam-magenta `#e1017a`, Bricolage Grotesque / Plus Jakarta Sans / JetBrains Mono, Lucide icons, lichte secties afgewisseld met navy "night" banden en één jam-gradient CTA-band.

## Stack

Eén `index.html` plus de logo-assets in `assets/` — geen build step. HTML + CSS + een paar regels vanilla JS (sticky nav, scroll-animaties, Lucide icons via CDN). Fonts via Google Fonts.

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
