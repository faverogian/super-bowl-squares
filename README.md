## Super Bowl Squares Average Payout Analysis

Gian Favero | February 2nd, 2024

With the Super Bowl around the corner, we try to find an edge in the popular "Super Bowl Squares" contest through Monte Carlo simulations based on NFL data gathered in the past ten years.

#### Background
Super Bowl squares is a popular betting game for football fans during the Super Bowl. Participants purchase squares from a 10x10 grid, resulting in 100 individual squares, each corresponding to the last digit of the score for each team. Winners are determined by matching the last number of each team's score with the grid each time a score occurs in the game. Typically, winners receive a fixed amount per score, with the rest being awarded as a grand prize at the conclusion of the game to the participant who owns the square corresponding to the game's final score. It's a game of chance that adds excitement to watching the Super Bowl, but could there be a way to maximize your odds?

#### Data
We leverage public NFL data from Stathead.com and Pro Football Reference to guide our mathematical process. Given the randomness and variability of sporting event outcomes, Monte Carlo simulations are run to get expected results at each phase of the process.

#### Constraints
Typically in such contests, participants have the ability to ``buy-in'' at a fixed dollar amount per square up to a certain number of squares. We wish to explore the best strategy for a participant to follow to maximize their chances at winning.

#### TL;DR
We run Monte Carlo simulations over the prospects of buying 1 to 10 squares in a Super Bowl Squares contest. We find that, surprisingly, one can expect to break even irrespective of the number of squares they buy if they play enough years in a row. To maximize the chances of profiting, participants should opt to choose 10 squares, as long run earnings are maximized doing so.
