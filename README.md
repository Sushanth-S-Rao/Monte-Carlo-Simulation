# Monte Carlo Simulation

Monte Carlo simulation is a model to predict the probability of various outcomes when the potential for random variables is present. It relies on repeated random sampling to obtain numerical results. It can be used analyze past data and predict a range of future outcomes based on a choice of action

## History of Monte Carlo Simulation
![image](https://github.com/Sushanth-S-Rao/Monte-Carlo-Simulation/assets/95978063/6669d136-70e4-4f0a-9a17-70faa59957cb)

## Description
###1) MonteCarloSimulation  
Simple demonstration of monte carlo simulation

Assume you need to complete 2 tasks. Based on the previous history, it would take anywhere between 1-5 hours and 2-6 hours to finish the tasks. If you can only spare 9 hours, determine the possibility that BOTH the tasks can be completed within 9 hours

When faced with significant uncertainty in making a forecast or estimate like this, some methods replace the uncertain variable with a single average number (i.e 3 hours for 1-5, 4 hours for 2-6). However this does not produce a feasible solution

The Monte Carlo simulation instead uses multiple values (by repeating random samples) and then averages the results. Repeating the sampling numerous times produces a better result as Principle of Ergodicity and Law of Large Numbers are the basis for Monte Carlo Simulation

Principle of Ergodicity describes the statistical behavior of a moving point in an enclosed system, the point will eventually pass every possible location  

Law of Large Numbers states that as the number of trials (or samples) increases, the average of the outcomes will converge to the expected value of the random variable  

\
###2) CasinoHouseAlwaysWins
How casinos exploit the monte carlo simulation to always win, eventually.

In order to lure people into gambling, casinos keep a small upper hand. Such as  
Rolling a dice with 1-49, Player wins  
Rolling a dice with 50-100, House wins  

Player starts with a fund of 10,000 dollars or so. And wages an amount of 100 or so.  
We simulate the different scenarios where player bets "n" number of times.  

With a few number of bets (n = 5, n = 10, n = 50), player can incur a profit or a small loss. The ideal strategy for a player is to place a small number of calculated bets and cash out quickly on making a profit.

With the more number of bets (n = 500, n = 1000, n = 5000), player incurs a loss majority of the times. The small upperhand the casino has becomes effective as the player bets more. In the end, the house always wins!

\
###3) Estimating Financial Risk through Monte Carlo Simulation  
Extracted from [github.com/alegaballo/AML](https://github.com/alegaballo/AML/blob/master/%5BLecture%207%2B8%5D%20Estimating%20Financial%20Risk%20through%20Monte%20Carlo%20Simulation.ipynb)



