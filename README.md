# tiny-chess-01-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/anhnd3005-infinity/tiny-chess-01-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/anhnd3005-infinity/tiny-chess-01-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Deterministic 4 KB pure-Python 3.13 stdlib bitboard chess engine built for [`tiny-chess-01`](https://make.fun/bounty/tiny-chess-01). Features Kindergarten sliding attacks, Zobrist hashing, PeSTO tapered evaluation with passed-pawn/king-safety/mobility/mop-up terms, PVS + iterative deepening, aspiration windows, 262k-entry transposition table, SEE-ordered captures, killer/countermove/history heuristics, NMP, LMR, RFP, and quiescence search under fixed deterministic node budgets.

## Run

```sh
python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=87xkrk03&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
