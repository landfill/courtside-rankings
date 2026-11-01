# courtside-rankings

Weekly ATP/WTA singles rankings (top 100) as static JSON, read by the COURTSIDE desktop app.

- `latest.json` — latest ranking date per tour and when it was last checked
- `index.json` — every ranking date stored here, per tour
- `rankings/{atp|wta}/{YYYY-MM-DD}.json` — one ranking list per official publication date
- `history/{atp|wta}/{id}.json` — one player's ranking history

Data is written by a scheduled GitHub Actions job in the app repository. Do not edit by hand.

## Sources and license

- Up to 2026-06-08: Jeff Sackmann / Tennis Abstract `tennis_atp` and `tennis_wta` datasets, CC BY-NC-SA 4.0 (https://creativecommons.org/licenses/by-nc-sa/4.0/).
- Later weeks: collected weekly from tennisapi.dev.

This data is shared for non-commercial use under the same CC BY-NC-SA 4.0 terms.
