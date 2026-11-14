# tiny-chess-01

Strongest chess engine in <=4 KB of Python, for the make.fun $500 bounty.

`main.py` is the whole engine: a rotate 120-board sunfish-style search with
transposition table, PVS, LMR, check extension, quiescence search and
piece-square evaluation. No model calls, no clock-based search, deterministic
fixed node budget.

Practice gauntlet (official kit scorer): trial-0 Elo 1326, trial-1 Elo 1173.
