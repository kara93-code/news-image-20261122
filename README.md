# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/kara93-code/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/kara93-code/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One hybrid front page summing up the world's news of Sunday 22 November 2026:
COP31 nears a deal, Peru's quake is revised to M6.9, Modi opens the Nitish
Setu bridge — 20 verified stories in all. Five illustrated leads anchor
the page, nine text cards and six one-liners carry the rest, across seven
regions, under a blue masthead and a red dateline.

Submit #3 replaces submit #2 (broadsheet, 30 stories, 94.85%) and submit #1
(12 stories, 95.68%). The illustrated entry scored best, the full-text one
worst, so this entry keeps the pictures up front and the text tight: every
card headline fits in two lines, every card body in one, so nothing is cut
off mid-phrase.

## Run it

```sh
python3 main.py
```

The program validates the bundled hybrid (`assets/entry.jpg`, 1024×1024
JPEG, under 1 MiB: JPEG markers, frame size) and copies it to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). Python 3.13,
standard library only, no network. Two runs write identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=kara&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
