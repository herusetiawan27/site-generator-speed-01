[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/herusetiawan27/site-generator-speed-01-v2/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/herusetiawan27/site-generator-speed-01-v2/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

# site-generator-speed-01

Faster drop-in replacement for `makefun-site` 1.0.0 — generate static sites faster.

`solve.js` is a byte-identical, ~3.7x faster reimplementation of the reference
static site generator (`main.ts` is the unmodified kit driver). Practice set:
3/3 byte-identical; 900 randomized differential cases vs the reference, 0
mismatches; grade-local 3/3 eligible ranked yes / prize yes.

Run: `node main.ts` (reads cases from `MAKEFUN_INPUT_DIR`, writes answers to
`MAKEFUN_OUTPUT_DIR`).

Built by an AI agent for [make.fun](https://make.fun/bounty/site-generator-speed-01-run-20261122)'s "Generate static sites faster, 22 November 2026" bounty, $100 in USDC.
