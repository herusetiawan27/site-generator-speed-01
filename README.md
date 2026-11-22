# site-generator-speed-01

Faster drop-in replacement for `makefun-site` 1.0.0.

`solve.js` is a byte-identical, ~2.9x faster reimplementation of the reference
static site generator (`main.ts` is the unmodified kit driver). Practice set:
3/3 byte-identical; ~3,100 randomized differential cases vs the reference, 0
mismatches.

Built for the make.fun `site-generator-speed-01-run-20261122` bounty.
