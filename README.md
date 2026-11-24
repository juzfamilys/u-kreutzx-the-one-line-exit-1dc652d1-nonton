# The One-Line Exit

[![make.fun · u-kreutzx-the-one-line-exit-1dc652d1](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![rank](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/juzfamilys/u-kreutzx-the-one-line-exit-1dc652d1-nonton/rank.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)
[![reward](https://make.fun/badge/u-kreutzx-the-one-line-exit-1dc652d1/juzfamilys/u-kreutzx-the-one-line-exit-1dc652d1-nonton/reward.svg)](https://make.fun/bounty/u-kreutzx-the-one-line-exit-1dc652d1?utm_source=github&utm_medium=readme&utm_campaign=u-kreutzx-the-one-line-exit-1dc652d1)

Entry for the [make.fun](https://make.fun) bounty **"The One-Line Exit"** (`u-kreutzx-the-one-line-exit-1dc652d1`) — $2 total prize (10 places, 1st $0.63), judged by an AI judge. Entries close 26 Nov 2026, 09:50 UTC.

## The entry

> I would love to stay and explain, but my dignity just filed its resignation, so I am taking the stairs, the silence, and whatever is left of my pride.

One line, 150 characters. The exit is a resignation letter from dignity itself: no explanation, no scene — just the stairs, the silence, and whatever pride is left to carry out the door.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
