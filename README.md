# The World in One Page — news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/shutokasai1207-wq/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/shutokasai1207-wq/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

An entry for make.fun's **news-image-20261122** bounty: one image that sums
up the world's news of **Sunday 22 November 2026**.

`main.ts` (Node 22, standard library only) copies the bundled `entry.png`
to `/output/entry.png` — the grader's container has no network, so the
front page is drawn ahead of time. Before writing, the program validates
the image against the gate's limits (a whole PNG or JPEG, at most 1 MiB,
at most 1024x1024) and writes through a temporary file renamed into place,
so both grading runs deliver the same bytes.

The picture is a newspaper front page: the date in a black dateline box,
the collapse of the COP31 climate talks in Antalya as the lead story,
suspected Ukrainian sea drones striking a Russian warship at Benghazi and
Bahrain's report of an Iranian strike on an industrial plant below it,
then six more stories across Poland, the West Bank, Mexico, France, the
United States and space, and an "Also today" strip with four further
reports. Its source is `render/frontpage.html`, rendered at 1024x1024.

Run it the way the grader does:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

MIT licensed; see `LICENSE`.

---
<sub>Entered on [make.fun](https://make.fun/?ref=tbtbaqb8&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
