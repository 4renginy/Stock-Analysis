#**Stock-Analysis**<br>
##**Overview of Project**<br>


Our new  clients wants to invest in the stock market. Since they are passionate about green energy particularly (DQ) we decided to create a diverced portfolio of green energy stocks to increase their chance to gain more return for their investment.  

We want to create Excell sheet showing total daily volume and yearly return for twelwe stocks for years 2017 and 2018. Daily volume will show how actively a stock is traded and the yearly return will show the % differance in the price from the beginning of the year to the end of the year. Based on the calculations we want help your clients to make best decition on their investments.

##**Method and Results**
Since we have an excell spreadsheet we used VBA code to automate the calculations. This helped us reduce the chance of errors and time to run the anaylsis especially if we needed to run it repeatedly.  
First we initialized an array for all tickers then initialized variables for the starting and ending prices for each ticker and total volumes. Looping through tickers and rows we found Total Valume , beginning and ending price for each ticker for year 2017 and 2018. To make the process faster , Instead of using ticker variable for each stock we created a tickerindex variable and it helped us to access the correct index for four different arrays. This refactoring helped the process to run 10 times faster.   
Whatever the method is used the result are as follow;  
**Year 2017**
Despite DQ had the lowest Total Daily Volume it had  highest return of 199.4 %.On the other hand SPWR had highest daily volume yet the return was only 23.1 %. Most successful stoks are DQ, SEDG, ENPH.
** Year 2018**
Last years winner DQ has lost 62.6 % of its value in 2018. RUN has the most return and ENPH has the highest daily volume for year 2018.  Year 2018 was not a good year for green stocks.

Looking at those 2 years results we can recommend to purchase ENPH, SEDG and RUN.

##**Summary**
Refactoring is intended to imporve the design and structure of the code without loosing functinlality. So it helps to make the design cleaner, easy to understand, easy to implement, and easy to maintain. Also it helps to perform faster with less memory usage. Although Refactoring has number of benefits, it is not a good idea to do it if the delivery deadline is near. The process could introduce bugs. Some cases cost of refactoring could be higher then rewriting the code from the scratch. Refactoring time consuming so tight scheduled projects should not be refactored.
If the original code is working without any issues and satisfies all teh necessities there is no need to refacture. 
