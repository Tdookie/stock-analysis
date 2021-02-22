# stock-analysis
## Overview of Project
### Purpose
The purpose of this project was to refactor the original code to collect all stocks in 2017 and 2018 to determine if these stocks will be profitable to invest in. The goal for this round was to increase the efficiency and respond time of the original code.
### Background
The data that is presented includes two charts with stock information on 12 different stocks. At the click of a button, Stev can analyze an entire dataset. Now, to do a little more research for his parents, he wants to expand the dataset to include the entire stock market over the last few years. Our code works well for a dozen stocks, but it might not work as well for thousands of stocks. And if it does, it may take a long time to execute. The stock information we refractored below contains a ticker value, the date the stock was issued, the opening, closing and adjusted closing price, the highest and lowest price, and the volume of the stock. The goal is to retrieve the ticker, the total daily volume, and the return on each stock.
## Results
![Screen Shot 2021-02-21 at 11 52 02 PM](https://user-images.githubusercontent.com/77812423/108664117-16bce680-74a0-11eb-809f-b15da6484f69.png)

The images shown above shows the analysis for stocks in 2017. The analysis shows that almost all tickers except for TERP had a positive return for the year. 

![Screen Shot 2021-02-21 at 11 59 30 PM](https://user-images.githubusercontent.com/77812423/108664488-dd38ab00-74a0-11eb-8092-2f8487f9de5d.png)

The images shown above shows the analysis for stocks in 2018. The analysis for 2018 shows that tickers "RUN" and "ENPH" were the only tickers that had a positive return for 2018.
## Summary
### Pros and Cons of Refactoring Code
Refactoring helps make our code cleaner, more organized, and more efficient. A few advantages of refactoring code include design and software improvement, debugging, and faster programming. It also benefits other users who have to read the code because it becomes easier to read because it is more concise and straightforward. However, we do not always get the opportunity to refactor our code due to disadvantages. These disadvantages include having applications that are too large to not having the proper test cases for the existing codes.

### The Advantages of Refactoring Stock Analysis
The most significant advantage that occurred as a result of the refactoring was an decrease in macro run time. The original analysis took approximately one second to run, whereas our new analysis only took about 0.15 seconds to run. Attached below are the screenshots that indicate the run time for our new analysis.


![Screen Shot 2021-02-22 at 12 18 08 AM](https://user-images.githubusercontent.com/77812423/108665679-78cb1b00-74a3-11eb-8828-180c783c8274.png)


![Screen Shot 2021-02-22 at 12 13 12 AM](https://user-images.githubusercontent.com/77812423/108665393-d01cbb80-74a2-11eb-9f1f-42d2e4d67e62.png)

