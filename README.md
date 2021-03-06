# stock-analysis

## Overview of Project
The project is about analyzing the performance of various stocks over a year period for different years with a view to recommending which stocks would make for better investment opportunities. The project also seeks to optimize code structures for better run time and minimal hardware resource requirement.

## Results
In 2018 only 2 of the analyzed stocks had good returns: RUN 84%, and ENPH 81.9%. However, RUN had 5.5% return in 2017. ENPH has the best return over a 2-year period and therefore would be the top recommended for investment opportunity.
As shown in the images that follow, the code structure used for analysis in VBA_Challenge is more efficient than that used for the same analysis in green_stocks as it had a faster runtime for both 2017 and 2018 analysis.

### 2017
![VBA_Challenge_2017](Resources/VBA_Challenge_2017.png)
![green_stocks_2017](Resources/green_stocks_2017.PNG)

### 2018
![VBA_Challenge_2018](Resources/VBA_Challenge_2018.png)
![green_stocks_2018](Resources/green_stocks_2018.PNG)

## Summary
The adavantages of refactoring code includes: it improves the design of software, makes them easier to understand, helps us find bugs and also helps in executing the program faster. The disadvantage of refactoring is that it could be time consuming.
The original code was refactored by including multiple tasks in the same For loop thereby reducing the runtime required for the analysis as shown in the results above. This improves the use of both machine time/resources, and man-hours. There was, however, a lot of time spent in refactoring the code. It's therefore concluded that refactoring is desirable overall.
