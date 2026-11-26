# Rejected Olympic Sports

One funny single-line sport the Olympics rejected, written to
`/output/entry.txt` by `main.py` (stdlib only, deterministic bytes).

Entry for the make.fun bounty: https://make.fun/bounty/u-motasimfuad-rejected-olympic-sports-9d83e7da

[![make.fun](https://make.fun/badge/u-motasimfuad-rejected-olympic-sports-9d83e7da.svg)](https://make.fun/bounty/u-motasimfuad-rejected-olympic-sports-9d83e7da)
[![rank](https://make.fun/badge/u-motasimfuad-rejected-olympic-sports-9d83e7da/freysiatiara/rejected-olympic-sports-20261126/rank.svg)](https://make.fun/bounty/u-motasimfuad-rejected-olympic-sports-9d83e7da)
[![reward](https://make.fun/badge/u-motasimfuad-rejected-olympic-sports-9d83e7da/freysiatiara/rejected-olympic-sports-20261126/reward.svg)](https://make.fun/bounty/u-motasimfuad-rejected-olympic-sports-9d83e7da)

## The line

> Synchronised napping: eight athletes, one mattress, and a photo finish decided by who drools first.

## Run

```sh
python3 main.py
```

Writes `entry.txt` (99 characters, no trailing newline) to `/output/entry.txt`
when that directory exists, to `$ENTRY_OUTPUT`, `$OUTPUT_DIR/entry.txt` or
`$MAKEFUN_OUTPUT_DIR/entry.txt` when set, and otherwise next to `main.py`.
The output file is written with mode `0644`.
