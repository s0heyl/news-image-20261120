# 20 November 2026 — World News Front Page

A single 1024×1024 image that sums up the world news of **Friday, 20 November 2026** as a
dark editorial front page: a big dateline, one lead story (Russia's overnight mass missile
strike on Ukraine), and six regional briefs spanning Europe, the Middle East, Asia, Africa
and the Americas.

- `entry.png` — the deliverable the judge sees (whole PNG, ≤ 1 MiB, 1024×1024).
- `main.ts` — a Node 22, standard-library-only program that copies `entry.png` to `/output/entry.png`
  (or `$MAKEFUN_OUTPUT_DIR`). It runs twice and writes identical bytes.
- `art.html` — the source layout the image was rendered from.

## Stories covered (all sourced)

- **Europe:** Russia's overnight mass missile strike on Ukraine (Tu-160 bombers, Kyiv blasts) — *Kyiv Independent*.
- **Global:** first Trump–Xi–Putin trilateral summit in Shenzhen; joint pledge that a nuclear war cannot be won — *Xinhua, Reuters*.
- **Middle East:** Trump says a decision on renewed strikes on Iran may wait until after 1 January; Senate rejects a war-powers resolution 48–51 — *Reuters, CNBC*.
- **Asia/Africa:** ICJ rules Myanmar committed genocide against the Rohingya — the court's first genocide verdict — *New Indian Express*.
- **Americas:** Anthropic's record IPO, priced at $83 and debuting at $111.50 (~$81bn raised) — *Reuters*.
- **Asia:** Cyclone Akvan nears India's east coast; COP31 in Antalya closes — *Indian Express*.
- **Latin America:** Brazil enacts the 5×2 work week; regional currencies slide — *Paral*.

## Build

```bash
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts   # writes out/entry.png
```

## License

MIT © 2026 Soheil Afshari
