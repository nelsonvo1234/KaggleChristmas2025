# KaggleChristmas2025

Benchmarking Ideas (just single run):
Greedy: 167.079200636702
Random Descent (200 Iterations, alter all params same time, reuse): 146.5621997192044210758737
Random Descent (200 Iterations, 1 param at a time, reuse): 241.4698390902593051133642
Random Descent (200 Iterations, alter all params same time, no reuse): too slow
Random Descent(200 Iterations, 8 Trees per Iteration, all params same time, reuse): 114.5949374970293141266175

Ideas to Try:
Maybe stop doing them based off each other, independent
I think it's time to try the probabilistic approach, I have no idea how first place did it though, their score is half of mine