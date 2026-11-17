# New-repository

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/elimi668/New-repository/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/elimi668/New-repository/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A strong chess engine in 4 KB of Python. 0x88 board, negamax with alpha-beta pruning, quiescence search, transposition table, null-move pruning, killer moves and repetition handling, under a fixed 120,000-node budget. Practice Elo 1364.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

`main.py` is the whole engine: at most 4,096 bytes as committed, Python 3.13, standard library only. It reads, imports or execs no other file in the repository. Search uses a fixed node count, never a clock, so trials replay deterministically.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
