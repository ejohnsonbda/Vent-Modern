# VentSafer — Modern Redesign

A clean, modern redesign of the VentSafer Secure Case Management Portal. This is a duplicate of the original [Vent](https://github.com/ejohnsonbda/Vent) repository with a fully redesigned UI/UX.

## What's New in v2 (Modern)

| Feature | Original | Modern |
|---|---|---|
| Design system | Basic CSS | Dark mode with CSS custom properties |
| Typography | System fonts | Inter (Google Fonts) |
| Login screen | Simple form | Glassmorphism card with animated blobs |
| Card layout | Basic grid | Hover animations, emotion badges |
| Analytics | Inline charts | Full dashboard with 5 chart sections |
| Filters bar | Flat inputs | Styled dark inputs with live stats |
| Modals | Basic dialogs | Polished `<dialog>` with backdrop blur |
| Scrollbars | Default | Custom styled |

## Pages

- **`index.html`** — Secure login + card grid console
- **`dashboard.html`** — Analytics dashboard with:
  - 4-stat overview (total entries, unique feelings, avg/month, active users)
  - Top 10 emotional states ranked list with bar chart
  - Monthly submission trends (last 6 months)
  - Emotional distribution (positive / neutral / negative)
  - User engagement metrics
  - 24-hour activity distribution chart

## Credentials

Login credentials are loaded from `passcore.json`. Fallback: `admin` / `8804114`.

## Data

All data is loaded from `evault_core.json` — the original anonymized emotional intelligence dataset.

---

*Duplicate of [ejohnsonbda/Vent](https://github.com/ejohnsonbda/Vent) — modernized UI only, no data changes.*
