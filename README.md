[![make.fun · sokoban-solver-01-run-20261121](https://make.fun/badge/sokoban-solver-01-run-20261121.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)
[![rank](https://make.fun/badge/sokoban-solver-01-run-20261121/aahcoba8-maker/makefun-sokoban-solver-01/rank.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)
[![reward](https://make.fun/badge/sokoban-solver-01-run-20261121/aahcoba8-maker/makefun-sokoban-solver-01/reward.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)

# Sokoban solver

A make.fun bounty entry: a push-optimal Sokoban solver in a single TypeScript file. It splits each level into rooms along the player's hallway, solves every room with a breadth-first search over pushes (dead-square and frozen-block pruning, canonical player regions), stitches the room solutions together, and writes the moves to /output/<id>/solution.txt. Run it with `node main.ts` on Node 22; MAKEFUN_INPUT_DIR and MAKEFUN_OUTPUT_DIR override the default /input and /output directories.
