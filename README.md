# soccer-picks — Telegram Mini App

The prediction sliders for **@soccdata_lab_bot** (Soccer Data Lab "beat the AI" ladder).
Static page served by GitHub Pages; the bot points `WEBAPP_URL` here.

- `index.html` — 3 sliders per fixture (Home / Draw / Away), default = the model's
  triple, normalized to sum 1; submits one JSON via `Telegram.WebApp.sendData`.
- `card.json` — the active matchday slate (regenerated each matchday by
  `src.content.build_card` and pushed here).

Source of truth lives in the private repo `football_data_lab` (`src/bot/`).
