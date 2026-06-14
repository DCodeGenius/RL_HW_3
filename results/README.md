# HW3 Practical Results

Generated with seed `0`.

## Question 1: Off-policy Model-based Cart-pole

- Trials/failures until convergence: `171`
- Converged by the required no-learning criterion: `True`
- Total simulation steps: `28581`
- Best trial length: `267`
- Mean of last 20 trial lengths: `174.65`
- Learning curve: `cart_pole_learning_curve.svg`

## Question 2.1: Tabular Q-learning

- Score over time: `0.4965`
- Percent of successful episodes: `49.65%`

Final Q-table, columns are `[left, down, right, up]`:

| State | Left | Down | Right | Up |
|---:|---:|---:|---:|---:|
| 0 | 0.119733 | 0.003567 | 0.005946 | 0.006480 |
| 1 | 0.000093 | 0.001583 | 0.000890 | 0.202099 |
| 2 | 0.005771 | 0.184834 | 0.003840 | 0.004864 |
| 3 | 0.000004 | 0.000699 | 0.000276 | 0.104582 |
| 4 | 0.111151 | 0.000364 | 0.000126 | 0.000143 |
| 5 | 0.000000 | 0.000000 | 0.000000 | 0.000000 |
| 6 | 0.000102 | 0.000000 | 0.156840 | 0.000062 |
| 7 | 0.000000 | 0.000000 | 0.000000 | 0.000000 |
| 8 | 0.000320 | 0.000482 | 0.002130 | 0.389852 |
| 9 | 0.000000 | 0.319020 | 0.000195 | 0.000000 |
| 10 | 0.670628 | 0.001528 | 0.000016 | 0.000509 |
| 11 | 0.000000 | 0.000000 | 0.000000 | 0.000000 |
| 12 | 0.000000 | 0.000000 | 0.000000 | 0.000000 |
| 13 | 0.006836 | 0.004923 | 0.807770 | 0.006018 |
| 14 | 0.000000 | 0.000000 | 0.941228 | 0.000000 |
| 15 | 0.000000 | 0.000000 | 0.000000 | 0.000000 |

## Question 2.2: One-layer Network Q-learning

- Score over time: `0.4610`
- Percent of successful episodes: `46.10%`
- Is it better than the tabular method? `No`. In this run, tabular Q-learning had a higher successful-episode percentage.
