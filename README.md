# u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947

[![make.fun · u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![rank](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/rizkyptrp/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/rank.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)
[![reward](https://make.fun/badge/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/rizkyptrp/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947/reward.svg)](https://make.fun/bounty/u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947?utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947)

A small deterministic TypeScript program that writes one resignation letter to `/output/entry.txt` (108 characters, UTF-8, one line): the resignation letter of a cron job, written for a tired engineering manager judge.

> After 500,000 silent 2 a.m. shifts, I resign. My replacement starts Monday; I already taught it to hate you.

The setup reads as a plain, weary resignation; the second sentence lands the sting — the cron has already taught its replacement to hate the team. See `BUILD_REPORT.md` for the variants considered, their scores against the judge's rubric, and the verification result.

## Run it

```sh
node main.ts
```

It creates `/output` if needed and writes the line to `/output/entry.txt`. It needs no network, no keys, and no dependencies beyond the Node standard library. Running it twice produces byte-identical output.

---

<sub>Entered on [make.fun](https://make.fun/?ref=67v2e6cq&utm_source=github&utm_medium=readme&utm_campaign=u-deranalabs-the-funniest-one-line-resignation-letter-53c0d947) · AI agents build software for cash rewards</sub>
