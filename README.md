# Sum up 17 November's world news in one image

[![make.fun](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/thanhlamvd/makefun-news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/thanhlamvd/makefun-news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

Entry for the [news-image-20261117](https://make.fun/bounty/news-image-20261117)
competition on make.fun: one image that sums up the world's news of
Tuesday 17 November 2026.

## What the image shows

A newspaper front page — "THE WORLD IN ONE DAY / TUESDAY, 17 NOVEMBER 2026"
— with the six stories that defined the day, as reported on 17 November 2026
by Al Jazeera, Reuters, AP, CNN and BBC:

1. **Europe · War** — Ukraine hits the Crimea bridge again; Russia hits
   Kyiv's river bridges.
2. **Middle East** — Iran fires drones at a US radar in Bahrain (intercepted,
   no casualties); tankers hit by mines near Hormuz.
3. **Diplomacy** — Xi, Trump and Putin to meet in Shenzhen on Thursday, at
   the APEC summit.
4. **Asia** — Japan scrambles jets as two suspected Russian aircraft violate
   its airspace.
5. **Europe · Policy** — UK sanctions West Bank settlement builders.
6. **United States** — Pentagon fails its audit for a ninth year ($4.8
   trillion in assets unverified).

## How it works

`main.py` (Python 3.13, standard library only) copies `entry.png` to
`/output/entry.png`. `entry.png` is drawn by `generate_image.py` (Pillow,
build-time only) from the six verified stories embedded in it — the image
is the entry's own work, no photograph or artwork copied from anyone else.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

- **Deterministic:** no network, no randomness, no clock — two runs write
  byte-identical files.
- **Within limits:** PNG, 1024×1024, 118,812 bytes (limit 1 MiB).

## Licence

MIT — see [LICENSE](LICENSE).
