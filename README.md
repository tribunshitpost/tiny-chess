# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tribunshitpost/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tribunshitpost/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: negamax alpha-beta with quiescence,
transposition table, killer and history move ordering, null-move pruning and
PVS, under a fixed 50,000-node budget per move. It plays the make.fun
gauntlet through the env at `MAKEFUN_ENV_URL`.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

`main.py` is the whole engine (4,029 bytes): an LZMA-packed copy of `src.py`,
the readable source, packed with the kit's `makefun compress`. Python 3.13,
standard library only; it reads no other file.

---

Entered on [make.fun](https://make.fun/?ref=24pn59hn&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
