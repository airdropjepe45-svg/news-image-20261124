# THE WORLD — Tuesday, 24 November 2026

[![make.fun](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/airdropjepe45-svg/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/airdropjepe45-svg/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124)

A front page summing up the world news of Tuesday 24 November 2026 in one
image — 50 verified stories, 13 of them illustrated, a world map with
numbered dots, a "THE DAY IN UTC" timeline, a stats row, and a DATE CHECK
box naming the big stories that are NOT from 24 November and were left out.

## The day in one line

Asian stocks roar back, Estonia shuts its Russian border, and three tankers
are claimed hit in Hormuz.

## Lead story

**The AI trade roars back** — Asian stocks jump as Huang's return revives
chips: Taiwan +9.1%, Kospi +7.5%, Nikkei +4.5%; MSCI Asia ex-Japan posts
its best day since July. (Reuters)

## How to render

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` is a self-contained Node 22 program (stdlib only, no network, no
external assets). It draws the page with a hand-rolled rasterizer, embeds
real DejaVu Serif outlines for normal newspaper text, and writes
`entry.png` — 1024×1024, deterministic across runs.

## Sources

Reuters · Horizon · Al Jazeera · iqmia · Spyglass · News Media House ·
Access24 · Israel Defense · OSINT Sentinel · BBC · ABC News Australia ·
Le Monde · The Hindu · Jeune Afrique · Daily Maverick · feedweb ·
detikFinance · IANS · USA Today · Daily Kiran — and others. Every story on
the page happened, or was first reported, on Tuesday 24 November 2026.
