# CLAUDE.md — ONUDI / Albaladejo deck (handoff)

Read this to resume without prior chat.

## What this is
A 17-slide single-file animated HTML deck (`index.html`, inline CSS + JS) presenting **Misión Digital's way of working to UNIDO (ONUDI)**. Audience: **Manuel Albaladejo**, UNIDO Representative for Argentina, Chile, Paraguay and Uruguay (Montevideo). (Brian sometimes phonetically writes "El Banarejo" / "Albaradejo" — same person.)

## Live + repo
- **Live:** https://mision-digital-onudi.netlify.app
- **GitHub:** riverplateconsulting/mision-digital-onudi (private). Standing rule: Misión Digital work belongs on the **brian@mision-digital.com** accounts (GitHub `BrianMision`, Netlify slug `brianmision`); migrating this off the riverplateconsulting accounts is a pending follow-up. Deploy: `source ~/.nvm/nvm.sh && nvm use 20 && netlify deploy --prod --dir=.`.

## Framing (locked by Brian — do not drift)
NOT a commercial pitch and NOT seeking a pilot. It simply shows "what we do" with dignity; things evolve naturally after. **No solicitation language anywhere.** Typographic bookend (no stock photo). Thesis: industrial sustainability needs verifiable data in the last meter of the chain, and that verifiable provenance is what Misión Digital builds. Heavy intellectual-honesty framing ("what we are / are not", "roadmap not shipped").

## Brand / design
Misión Digital house style (the parent brand book): **cyan `#2EA9E6` primary, teal `#00747F` mandate accent, indigo `#2D3566` dark sections on white**; HEATING orange `#D3731B` only as a ~5% accent (per maintenanz.com). Fonts: **IBM Plex Sans Condensed** (display), **IBM Plex Sans** (body), **IBM Plex Mono** (labels). The **Misión Digital logo** is in the chrome, a persistent footer lockup, the cover and close (`assets/logo-blue.svg`, `assets/logo-white.png`). The **Makkie robot** mascot appears on cover/obstáculo/incentivo/cierre (`assets/robot-*.png`), larger and pulled inboard. NEVER the word "maintenance"/"Maintenanz". Rioplatense, no em dashes. Canon verbiage from the original decks is used (Operamos en, El programa de oficina ofrece, Por Lo Menos / Ahorro de Tiempo, etc.).

## Conventions / gotchas
- All slides are vertically centered (`.slide { justify-content: center }`). `?reveal` URL flag forces reveal states for headless capture; the `.deck` is a scroll container so hash anchors land ~1-2 slides off in headless (verify in a real browser).
- Interactions: clickable 8-tab work-order strip (Medidas = the configurable indicator slot), Gobierno node cycles Norma CO / MRV / circularidad, zoom-out field, 60% count-up, bridge connectors.

## Status
Shipped, audited (a11y/contrast/responsive bulletproofing applied), live. The brand framework reference: `Downloads/Misión Digital/assets/Maintenanz Color Scheme Company Design.pdf`; logos in `Downloads/Misión Digital/Assets/OneDrive_1_4-25-2026/`.
