# EmpiricalHundredPrisonersTest

A program that simulates the 100 Prisoners Problem using the proposed optimal strategy N times and reports the average success rate.  

The notebook explores the problem of the hundred prisoners, which proposes the following scenario:
- There are 100 prisoners, each assigned a number from 1 to 100.
- There are 100 boxes, each labeled from numbers 1 to 100, and each box has a number of a random prisoner inside of it.
- If all prisoners find their own number, they are all set free. If even one prisoner fails, all are executed.
- Prisoners cannot communicate after the search begins, but they may agree on a strategy beforehand.
- Prisoners cannot see the other performing their search.
- Each prisoner performs their search alone and must leave the boxes exactly as they were found.
- Each prisoner has only 50 attempts to find its own number, meaning they may open at most 50 boxes.

Considering the probabilities, there a very small chance that the prisoners will be freed if they choose the boxes at random. 

However, there is in fact a proposed optimal strategy to solve this problem. Since the purpose of this notebook is solely to empirically demonstrate that the proposed approach delivers the promised chance of success, I will avoid further explanation.

Fortunately, the more detailed information about this problem and the proposed optimal strategy to solve it can be found on the following wikipedia page: https://en.wikipedia.org/wiki/100_prisoners_problem.