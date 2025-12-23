# KaggleChristmas2025

Benchmarking Ideas (just single run):
Greedy: 167.079200636702
Random Descent (200 Iterations, alter all params same time, reuse): 146.5621997192044210758737
Random Descent (200 Iterations, 1 param at a time, reuse): 241.4698390902593051133642
Random Descent (200 Iterations, alter all params same time, no reuse): too slow

Ideas to Try:
Parallel threading so I can do multiple at a time (working on this rn)
Maybe stop doing them based off each other, independent