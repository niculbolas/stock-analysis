# stock-analysis
## Overview of Project:
The purpose of this project was to do some analysis on various stocks for our friend Steve in order to determine whether or not the investments that his parents were making were good or not.  Secondly, after an initial try at such an analysis we also wanted to refactor or optimize the code we created in order to run more efficiently.

## Results:
The stock that Steve's parents had invested in has ticker DQ.  Looking at the pictures below, it is easy to see that during the year 2017 there was a return gain of 199.4% and during the year 2018 there was a return loss of 62.6%.  In other words, the stock performed well in 2017 but then had an abyssmal year in 2018.  In fact, looking at the data, most of the tracked stocks showed a gain in 2017 and then a loss in 2018.

### 2017 Results:
![2017](/Resources/2017Chart.png)

### 2018 Results:
![2018](/Resources/2018Chart.png)

## Refactoring:
The code we used to originally perform this analysis was rewritten in order to make it run more efficiently.  There was definately a gain in performance.  See the pictures below in order to compare the script run times both versions of code.  There is a marked reduction in script runtime for both years.

### 2017 Script Run:
Before:

![2017 Before](https://github.com/niculbolas/stock-analysis/blob/main/Resources/VBA_Challenge_2017%20(Original%20Script).png)

After:

![2017 After](https://github.com/niculbolas/stock-analysis/blob/main/Resources/VBA_Challenge_2017%20(Refactored%20Script).png)

### 2018 Script Run:
Before:

![2018 Before](https://github.com/niculbolas/stock-analysis/blob/main/Resources/VBA_Challenge_2018%20(Original%20Script).png)

After:

![2018 After](https://github.com/niculbolas/stock-analysis/blob/main/Resources/VBA_Challenge_2018%20(Refactored%20Script).png)
## Summary:
Q: What are the advantages or disadvantages of refactoring code?
A: One of the primary advantages to refactoring code is that it can make the code run more efficiently, thus saving time and energy to accomplish the same task.  Another advantage, is that in the process of refactoring code it can be made more easy to read and understand and more detailed comments can be added.  The biggest drawback that I can see to refactoring code is that there is an investment of time to be made.  If the code already works, then does the increased efficiency negate the time investment required to refactor the code?  An argument could be made either way.

Q: How do these pros and cons apply to refactoring the original VBA script?
A: In this particular case, I do not think that this code needed to be refactored.  The script already ran in less than 1 second on my machine before it was refactored.  Yet, to refactor the code I spent a significant amount of time to gain a fraction of a second in runtime.  The trade off here was not worth it.
