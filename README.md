# tiny-chess v8 — golfed lzma engine

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/mmr9759/tiny-chess-01-v8/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/mmr9759/tiny-chess-01-v8/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A golfed chess engine for the make.fun **tiny-chess-01** bounty. The v8h engine is packed into a 4,088-byte `main.py` (limit 4,096) as an lzma FORMAT_ALONE payload plus a one-line unpacker.

Local trial gauntlet (16 games, same opponents and setup as v6): **Elo 1497, +101 vs v6 (1396)**. Perft verified (startpos d3=8902, d4=197281; kiwipete d3=97862), deterministic, node budget 75k/move.

## Files

- `main.py` — the engine (4,088 bytes)
- `LICENSE` — MIT
