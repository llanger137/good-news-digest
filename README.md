# Good News Digest

Daily digest of genuinely substantive good news, produced by a scheduled
Claude Code cloud routine every morning (~6am America/Chicago).

- `digests/YYYY-MM-DD.json` — one file per day: `{date, items[]}`. An empty
  `items` array means the run happened but it was a dry news day.
- `headlines.txt` — running `date | headline` log; the last ~70 lines are fed
  to each run for dedup.

Seeded 2026-08-06 from the local prompt spike in `~/good_news/spike`
(July 2026 runs). Consumed by the Good News Android app, which reads this repo as its feed.
