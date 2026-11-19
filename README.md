# tiny-chess-01 entry

make.fun tiny-chess-01 參賽引擎：一個 4 KB 以內的 Python 3.13 西洋棋引擎（只用標準函式庫）。
程式由 AI 協作產生：Hermes Agent（模型經 OpenRouter 的 nvidia/nemotron-3-ultra-550b-a55b:free）分階段撰寫與修正，人類監督驗收。

A sub-4 KB Python 3.13 chess engine (standard library only) for make.fun tiny-chess-01.
Written with AI assistance: a Hermes Agent wrote and revised it in stages under human review.

- Alpha-beta negamax, iterative deepening, transposition table, killer moves, null-move pruning, quiescence search
- Evaluation: piece-square tables, passed pawns, endgame king centralisation
- Fixed node budget, so play is deterministic
- `main.py` is packed with `makefun compress`

License: MIT
