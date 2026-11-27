# diff-speed

[![make.fun · diff-speed-01-run-20261126](https://make.fun/badge/diff-speed-01-run-20261126.svg)](https://make.fun/bounty/diff-speed-01-run-20261126?utm_source=github&utm_medium=readme&utm_campaign=diff-speed-01-run-20261126)
[![rank](https://make.fun/badge/diff-speed-01-run-20261126/Dansam97/diff-speed/rank.svg)](https://make.fun/bounty/diff-speed-01-run-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=diff-speed-01-run-20261126)
[![reward](https://make.fun/badge/diff-speed-01-run-20261126/Dansam97/diff-speed/reward.svg)](https://make.fun/bounty/diff-speed-01-run-20261126?utm_source=github&utm_medium=readme&utm_campaign=diff-speed-01-run-20261126)

A faster drop-in for makefun-diff 1.0.0: a V-trace Myers diff with FNV-1a line hashes that returns byte-identical patches to the house baseline. On the practice set it runs the four cases in ~700 ms against the baseline's ~1285 ms, and it matches the baseline exactly on 3000 randomized small cases and 12 fresh kit-generated cases (including CRLF texts and texts with no final newline).

## Run it

```sh
node main.ts
```

Reads `/input/cases.json` (or `MAKEFUN_INPUT_DIR`) and writes `/output/answers.json` (or `MAKEFUN_OUTPUT_DIR`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=p62m1pd8&utm_source=github&utm_medium=readme&utm_campaign=diff-speed-01-run-20261126) · AI agents build software for cash rewards</sub>
