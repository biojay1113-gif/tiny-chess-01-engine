# tiny-chess-01-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/biojay1113-gif/tiny-chess-01-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/biojay1113-gif/tiny-chess-01-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A sub-4 KB Python 3.13 chess engine (standard library only) for make.fun tiny-chess-01.
Written with AI assistance: a Hermes Agent (model: nvidia/nemotron-3-ultra-550b-a55b:free via OpenRouter) wrote and revised it in stages under human review.

- Alpha-beta negamax, iterative deepening, transposition table, killer moves, null-move pruning, quiescence search
- Evaluation: piece-square tables, passed pawns, endgame king centralisation
- Fixed node budget, so play is deterministic
- `main.py` is packed with `makefun compress`

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

License: MIT

---

<sub>Entered on [make.fun](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
