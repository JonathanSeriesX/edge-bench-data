# edge-bench-data

Raw measurement data for [edge-bench](https://github.com/JonathanSeriesX/edge-bench),
kept in its own repo so benchmark rounds never trigger app deploys.

- `raw/*.ndjson` — one JSON object per probe per platform per round, append-only
- `summary.json` — the rolling 7-day rollup the dashboard fetches at runtime

Every commit is one collection round, pushed by the public GitHub Actions
workflow in the main repo.
