### GitHub Package Overview: Statistics, Probability, Odds

The upcoming GitHub package focuses on lottery analytics tools based on statistical methods, probability theory, and odds calculation. It's designed to help users understand and potentially enhance their approach to playing lotteries through a programming lens, not too advanced but clear enough for those with basic understanding.

#### Understanding Probability in Lotteries

The essence of lotteries is randomness; they are games of chance where outcomes are unpredictable. Despite this, probability theory allows us to analyze lottery draws systematically. The basic probability of asserting a winning number in a typical lottery setup is calculated using the formula:

      $$
      \text{Probability} = \frac{\text{Number of favorable combinations}}{\text{Total number of combinations}}
      $$

#### Statistical Analysis: Hot and Cold Numbers

One popular method among players involves analyzing "hot" and "cold" numbers. Hot numbers are those that appear frequently, while cold numbers appear less often. This package will include functions to quickly identify these numbers based on historical data, allowing users to experiment with different combinations of hot, cold, or mixed numbers.

#### Combinatorial Mathematics and Odds

The package also integrates combinatorial mathematics to enhance understanding of number groupings, such as odd/even or high/low numbers. The formula for odds, which provides a different perspective than probability, is given by:

      $$
      \text{Odds} = \frac{\text{Number of favorable combinations}}{\text{Total number of combinations} + \text{Number of favorable combinations}}
      $$


This approach helps compare favorable outcomes (winning scenarios) against unfavorable ones (losing scenarios).

#### Practical Applications

The package will feature a program that calculates the probability of winning based on different lottery scenarios:
1. Numbers ranging from 1 to 100
2. Numbers ranging from 1 to 999
3. Numbers ranging from 1 to 4999

These tools aim to provide users with a clearer understanding of the statistical and probabilistic dynamics at play in lottery games. By combining different mathematical tools and theories, the package seeks to offer a practical yet insightful approach to tackling the uncertainties of lottery outcomes.

### Rerequirements


requests>=2.25.1

numpy>=1.19.5

pandas>=1.2.0

matplotlib>=3.3.4

scipy>=1.6.0

notebook>=6.2.0

### Credits
Edvin Hiltner
