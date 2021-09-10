# Stock-Analysis

## Overview of Project

In order to select the best stock for investment, we created workbook to analyse stocks performance in 2017 and 2018. Stock performance includes the total volumn throughout the year and the return at the end of the year for each stock.

## Results

- The stocks are performing better in 2017 than in 2018.
- In 2017, only one stock (TERP) showed negative return, while all others stocks had a positive growth at the end of the year.
![Stock2017](https://github.com/swang202/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017-stock.png?raw=true)

- In 2018 however, only two stocks (ENPH and RUN) showed positive returns at the end 2018. Prices of other stocks decreased from -3.5% to -62.6%.
- ![Stock2018](https://github.com/swang202/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018-stock.png?raw=true)

- The elapsed run time for the refactored code are less than 1s. It is slightly slower in analysing 2017 (0.6721191s) than 2018 (0.637207s).
- ![time2017](https://github.com/swang202/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png?raw=true)
![time2018](https://github.com/swang202/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png?raw=true)

## Summary
### Refactoring code
- Advantages:
  1. Optimize and increase the efficiency of the code, which saves memory of the operating system.
  2. With reduced steps and improved logical of the code, it's easier to understand and maintain.
  3. Good for adapting code from someone else.
  
- Disadvantages: 
  1. Time consuming while not adding any new functionality.
  2. Might accidently introduce bugs.

### Applying refactoring to vba script
- pros: Help to recognize abstract patterns in the vba script. We can re-use the code easier to solve similar problems and applying it to future analysis.
- cons: Without adding more functionality, it might not worth the time or effort. Especially in the case where refactoring only improve the code execution time by miliseconds.