# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/nindafahila/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/nindafahila/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Strongest chess engine in <=4 KB of Python, for the make.fun $500 bounty.

`main.py` is the whole engine (4,046 bytes): PeSTO-style tapered
piece-square evaluation, alpha-beta search with quiescence, killer/history
move ordering and null-move pruning. No model calls, no clock-based search,
deterministic fixed node budget.

Practice gauntlet (official kit scorer): Varian E averages Elo 1,427
(trials 1,545 / 1,545 / 1,191), 11.5/18 vs the 1,276-Elo baseline (9.0/18).
14/14 local checks pass. The round-2 entry is already in the final at Elo 1,364.
