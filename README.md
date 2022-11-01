# stocks-analysis
Analyzing stocks data using VBA
## Resualts
* Analyzing stocks data using VBA I want to present  the total daily volume and yearly return for each stock. Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. The yearly return is the percentage difference in price from the beginning of the year to the end of the year.Looking at the data, we will concentrate on two results, the total returns for the years 2017 and 2018 and the execution times for the performance of the VBA code (orgininal code vs. refactored code).Comparing stocks returns for the year 2017 vs. 2018 year we can conclude that our stock portfolio (consisted of green energy stocks) was outperforming in 2017, compared to 2018. In 2017 we had 11 stocks making positive returns, some making almost 200 % return for the following year ("DQ" 2017=199.4% return). On the other hand 2018 was a year with low, negative returns (only two stocks had positive returns for the year "ENPH" and "RUN"). Taking into consideration volume of traded stocks we can see that  trading activity drop in 2018. Number of positive returns in 2017 suggest that 2017 was a great "bull run" for green energy stocks ( "Bull markets" occur when there is a sustained rise in stock prices, and they are typically accompanied by elevated consumer confidence, low unemployment, and strong economic growth.) Considering 2018 returns we can conclude that investing in green energy stocks wasn't a lucrative investment. If we focus our attention on individual stocks "DQ" might not be a good overall pick considering both years, compared to "ENPH" stock.
* Measuring code "run times"  (2017 original code time of 0,6171875 sec vs. 2017 refactored code time of 0.1328125 sec and 2018 original code time of 0.5859375 sec vs. 0.09375 sec) we can conclude that refactoring the code speed up our code performance.

![This is an image](https://github.com/MilosPopov007/stocks-analysis/blob/main/AllStockAnalysis_2017.png)
![This is an image](https://github.com/MilosPopov007/stocks-analysis/blob/main/AllStockAnalysis_2017_Refactored.png)
![This is an image](https://github.com/MilosPopov007/stocks-analysis/blob/main/AllStockAnalysis_2018.png)
![This is an image](https://github.com/MilosPopov007/stocks-analysis/blob/main/AllStockAnalysis_2018_Refactored.png)
* [VBA CODE-Refactored](https://github.com/MilosPopov007/stocks-analysis/blob/main/VBA_Challenge_Refactored_CODE.txt)


### Summary
* Refactoring is a key part of the coding process.When refactoring code, we want to make the code more efficient—by taking fewer steps, using less memory, or improving the logic of the code to make it easier for future users to read.However, since refactoring does not tamper with the functionality of the application, you cannot add new features. It also requires robust skillsets to simplify the code, as the process is often complex. [^1]
[^1]: https://modlogix.com/blog/legacy-code-refactoring-tips-steps-and-best-practices/
* In our refactored code we wanted to break down the process to be more efficient and logical when using for loops to process data. Disadvantages of our refactoring was that it takes time to apply changes to original script.Developing new bugs and defects was high while refactoring.
