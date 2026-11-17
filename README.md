# The APR Blind Spot — Holiday Debt Payoff Calculator

Interactive calculator for Freedom Debt Relief (Fractl DJC campaign "The APR Blind Spot").
Shows when a card balance could be paid off at a fixed monthly payment, and how much extra
time and interest planned holiday spending adds.

- Single file: `index.html`. Styled to the FDR brand tokens in the client's calculator library (primary #154199, CTA red #CB000E, text #2F2F2F, page #F9F9F9, 8px radius).
- One external request: the DM Sans web font from Google Fonts. The font stack leads with Ultramarine, so a host page that already loads it will use it; without either font it falls back to Helvetica/Arial.
- **To serve it:** Settings → Pages → deploy from `main`, root (`/`). The tool loads at the Pages URL.
- Educational estimate only: fixed monthly payment, constant APR, no new charges beyond the holiday amount.

Source: Freedom Debt Relief study.
