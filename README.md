# Tiny Chess

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/onnyh/tinychess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/onnyh/tinychess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A chess engine in a single `main.py` (<= 4 KB): negamax alpha-beta with
iterative deepening under a fixed 100,000-node budget, quiescence search,
transposition table, PVS, null-move pruning, late-move reductions, killer and
history ordering, and material + piece-square-table evaluation with a
phase-switched endgame king table. `main.py` unpacks and execs an
lzma-compressed payload contained in its own bytes; Python standard library
only, fully deterministic.
