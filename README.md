# Big Arch Motion Ad (study)

30-second 16:9 motion-graphic ad concept ("주문은 랩으로 받는다") built as a single HTML page with Web Audio sound design and kinetic typography.

- `bigarch_ad_v2.html` — current version (Big Arch · McFlurry · Coca-Cola Original set)
- `bigarch_ad.html` — v1 draft
- `analyze.html` — BPM / energy analysis used to pick and sync the BGM

## Run
Serve the folder locally (the BGM is loaded with `fetch`):

```bash
python -m http.server 8765
```

Open http://localhost:8765/bigarch_ad_v2.html and click to play.

## Credits & notice
- Music: "Hard Boiled" by Kevin MacLeod (incompetech.com), licensed under CC BY 4.0 — https://creativecommons.org/licenses/by/4.0/
- Non-commercial study project. Not affiliated with or endorsed by McDonald's or The Coca-Cola Company; all trademarks belong to their owners. Product art is illustrated, not official imagery.
