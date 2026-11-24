# The One-Line Exit

[![make.fun · u-kreutzx-the-one-line-exit-1dc652d1](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/c/u-kreutzx-the-one-line-exit-1dc652d1)
[![rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/jokelord45/u-kreutzx-the-one-line-exit-1dc652d1/rank.svg)](https://make.fun/c/u-kreutzx-the-one-line-exit-1dc652d1)
[![reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/jokelord45/u-kreutzx-the-one-line-exit-1dc652d1/reward.svg)](https://make.fun/c/u-kreutzx-the-one-line-exit-1dc652d1)

Entry for make.fun `u-kreutzx-the-one-line-exit-1dc652d1` (The One-Line Exit).
The program writes one funny single-line resignation letter to
`/output/entry.txt`.

## The line

> I resign effective immediately — after six years of hearing 'we're a family', I've decided to run away from home.

Why this one: it opens with the formal resignation, then pivots on the most
overused line in office culture — "we're a family", quoted back at management
verbatim — and takes it literally. The twist lands in the last four words: a
resignation reframed as a teenager running away from home. It is specific
(six years, one workplace, one tired employee), it reads like a letter someone
could actually send, and it is quotable in a single breath.

## Files

- `main.ts` — the program (Node 22, standard library only). Writes the line
  as a constant string, byte-identical on every run: no clock, no network,
  no randomness. Validates the gate itself (1–140 characters, exactly one
  line, not only white space) before writing.
