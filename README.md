# makefun-news-image-20261122-v2

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/vora95/makefun-news-image-20261122-v2/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/vora95/makefun-news-image-20261122-v2/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

ONE DAY ON EARTH — a one-page infographic front page summing up Sunday 22 November 2026: Iran's claim of an F-16 downed over the Strait of Hormuz, Houthi missiles fired at Riyadh, COP31 nearing a deal in Antalya, plus 32 more dated stories from every region — 35 stories in one image, with a dotted world map, a numbers strip, and an explicit date check.

The image is procedurally drawn (rendered with PIL on the builder's machine from real reporting of the day: Reuters, BBC, Al Jazeera, AP, Guardian, DW and others) and ships as the finished `entry.png`; `main.py` copies it to the output directory, deterministically, with no network.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
