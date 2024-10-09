# CI2024_lab1
### Results

| Universe size | Num sets | Density | Steps | Cost | Algorithm |
| ------------- |----------|---------|-------|------|-----------|
|100|10|0.2|293|283.5| Simulated Annealing |
|1000|100|0.2|6123|6323.6| Simulated Annealing |
|10000|1000|0.2|4411|128857.6| RHMC |
|100000|10000|0.1|998|69856958.1| RHMC |
|100000|10000|0.2|997|155340361.4| RHMC |
|100000|10000|0.3|988|236477054.2| RHMC |

To solve the set cover problem, I wrote two algorithms:
I continued the solution started by the professor in class with the RHMC, adding tabu search, and then I implemented Simulated Annealing, aiming to optimize the fitness function and the multiple_mutation function, seeking to improve the initial solution using a greedy algorithm during a random restart.

I noticed that Simulated Annealing performs better for smaller values, while RHMC is better for larger values. Additionally, I set different maximum step values because, for high values, the code took too long to reach a result.