# tiny-chess-01

A deterministic chess engine in a single Python file. `main.py` searches each position with iterative deepening, alpha-beta, and a fixed node budget, extends checks, and scores captures in a quiescence search. Evaluation is material plus piece-square tables. It talks only to the contest environment over HTTP and never calls a model.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/TaylorFourier/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/TaylorFourier/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

## Run it

```
python3 -P -s main.py
```

Set `MAKEFUN_ENV_URL` to the contest environment. The process plays every game, then exits when the env reports `status` `done`.

<sub>Entered on [make.fun](https://make.fun/?ref=n9dm78x1&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
