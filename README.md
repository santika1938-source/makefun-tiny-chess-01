# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/santika1938-source/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/santika1938-source/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4 KB of Python: negamax alpha-beta search with quiescence (check evasions included), a transposition table, null-move pruning, late-move reduction, and material + piece-square evaluation with king shelter and bishop-pair terms. It searches to a fixed node budget, never to a clock, so every replay plays the same moves. `main.py` is the whole engine (packed with the kit's compress command from its readable source); it talks to the env at `MAKEFUN_ENV_URL` and plays the gauntlet in UCI.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

---
<sub>Entered on [make.fun](https://make.fun/?ref=1c6jcmp6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
