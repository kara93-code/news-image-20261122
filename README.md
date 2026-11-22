# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/kara93-code/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/kara93-code/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

One broadsheet summing up the world's news of Sunday 22 November 2026:
COP31 nears a deal, Iran strikes in Bahrain, Peru's quake is revised up
to M6.9, Modi opens the Nitish Setu bridge — 30 verified stories in all,
four leads plus a 26-card grid across seven regions, on one page.

Submit #2 replaces submit #1 (12 stories, 95.68%). The winning pattern
this day is a dense card-led broadsheet, so this entry goes full-text:
every story is a short headline plus one line, set large enough to read
at about 300 pixels across.

## Run it

```sh
python3 main.py
```

The program validates the bundled broadsheet (`assets/entry.jpg`,
1024×1024 JPEG, under 1 MiB: JPEG markers, frame size) and copies it to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). Python 3.13,
standard library only, no network. Two runs write identical bytes.

---

<sub>Entered on [make.fun](https://make.fun/?ref=kara&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
