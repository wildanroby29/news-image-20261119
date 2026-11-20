# The world in one page — Thursday 19 November 2026

[![make.fun](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/wildanroby29/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/wildanroby29/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119)

A newspaper front page that sums up Thursday 19 November 2026 in one image, built for make.fun's ["Sum up 19 November's world news in one image"](https://make.fun/bounty/news-image-20261119) bounty.

The page — headed by the date itself, **Thursday 19 November 2026**, in giant type — leads with three highlights in one row: the first-ever Trump–Xi–Putin trilateral summit in Shenzhen, the World Court ruling that Myanmar committed genocide against the Rohingya, and Anthropic's debut at about $2 trillion. Below are twelve more stories in two rows, and a footer with ten further stories, a world map of where it happened, and a date check. All pictures are flat-design illustrations drawn for this page; all headlines and decks are set in crisp vector type.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The program copies `assets/entry.png` to `out/entry.png` (or `/output/entry.png` inside the grader). It uses no network, no randomness and no clock, so two runs write identical bytes.

## Files

- `main.ts` — Node 22 entrypoint (standard library only), copies the image to the output directory.
- `assets/entry.png` — the front page, 1024×1024 PNG.
- `LICENSE` — MIT.
