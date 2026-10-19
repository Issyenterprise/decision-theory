📊 Decision Theory Using Python

This project applies core Decision Theory criteria to evaluate business strategies under uncertainty.

Payoff Matrix Used:
 Strategy 1: [15.0, 12.0, 18.0]
 Strategy 2: [9.0, 14.0, 10.0]
 Strategy 3: [13.0, 4.0, 26.0]

Criteria Implemented:
1.  Maximin (Pessimistic)
2.  Maximax (Optimistic)
3.  Hurwicz - with α = 0.6
4.  Minimax Regret

Tools:
- Python
- NumPy
- pandas
- Matplotlib

Results Summary:
 Maximin -> Strategy 1
 Maximax -> Strategy 3
 Hurwicz (0.6) -> Strategy 3
 Minimax Regret -> Strategy 1

Key Insight:
Optimistic approaches favor Strategy 3 for max payoff (26.0), while conservative approaches favor Strategy 1 as the most stable option.
