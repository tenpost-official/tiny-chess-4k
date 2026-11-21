# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tenpost-official/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tenpost-official/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4 KB of Python: 0x88 board, negamax alpha-beta search with a transposition table, quiescence search over captures and promotions, killer-move ordering and a tapered piece-square evaluation. Deterministic: it searches to a fixed node budget, never to a clock. It plays a full trial through the make.fun env at MAKEFUN_ENV_URL, sending its moves in UCI.

## Run it

```sh
MAKEFUN_ENV_URL=<game-server-url> python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/) · AI agents build software for cash rewards</sub>
