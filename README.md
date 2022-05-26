# VBA_Challenge

## Overview of Project

Steve liked the original code we supplied him to analyze stock data. Now, he would like to analyze a much larger data set so he has requested we refactor the code to run more efficiently. To do this we will have to look at the original code, analyze areas which improvements can be made, and edit the code to run more efficiently.

## Results

Based on the results, the stock market performed much better in 2017 than in 2018. In 2017 all but one stock showed a positive return with four of the 12 stocks analyzed showing returns of over 100%. In 2018 only two stocks showed a positive return and both were in the 80% return range. 

After refactoring the code the speed has increased 4 fold. To achieve this increase we created two i loops and inserted them before the j loop and after the j loop. In the original code all 3013 lines of data were run for each i value of 0 to 12 because the j loop was nested inside of the i loop. In this new code the 3013 lines of data are only run once since the j loop is no longer nested inside of the i loop. In essence, we can process 33,143 less lines of data this way.

## Summary

In summary, I think the advantages of refactoring code is that the efficiency of the code can be increased without starting from scratch. The main disadvantage though is changing one area of the code can break another area which can result in large time sinks. This is especially prevelent if the code does not have accurate commenting or it has been a while since the code was touched. Another disadvantage is refactoring may not be worth the time investment depending on how efficient the original code is. In each case time value should be taken into account.

When it comes to refactoring the original VBA script, the cons can be mostly mitigated by having good comments. Knowing what each section of code is mean't to do will help find areas where the code can be improved but also spot issues. It can also help a programmer determine if it is worth the time investment to refactor the code.
