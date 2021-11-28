# Stocks Analysis

## Project Overview
The purpose of this project is to refactor Module Two's Visual Basic for Applications (VBA) solutiuon code to determine whether refactoring allows the code to run faster. The application of this change required altering the code to loop through the data once, instead of several times. 

## Results

##### Fig 1 & 2. 2017 vs 2018 Stock Returns
![fig1](https://github.com/retroxsky06/stocks-analysis/blob/main/Resources/Return2017.png) 
![fig2](https://github.com/retroxsky06/stocks-analysis/blob/main/Resources/Return2018.png)

Based on the analysis, the results show that the 12 stocks performed better in 2017 than 2018.  Only one stock 2017 had a negative return, whereas 2018 had 10 negative returns.  Since majority of the analyzed stocks seemd to do poorly in 2018, external factors may have impacted the stocks, thus further research and analysis is needed to provide any stock recommendations.

#### Refactoring Code
##### Fig 3 & 4. Run time for refactored code
![fig4](https://github.com/retroxsky06/stocks-analysis/blob/main/Resources/Refactor217.png) 
![fig3](https://github.com/retroxsky06/stocks-analysis/blob/main/Resources/Refactor2018.png) 

After refactoring the code, the run time was reduced from 0.51 secs to 0.10 secs. As seen in the images above, the run-time is improved regardless of the selected year (2017 or 2018).

## Summary
Refactoring code is a very important process as it makes code more efficient and maintanable. Although refactoring may create easier to read and/or understand code, there are disadvantages such as breaking your code, and needing to figure out where and how to debug the refactored code (time-consuming).



