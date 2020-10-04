**__Stock-Analysis__**<br>
<br>
**Overview of Project**<br>
*******************************


Our new  clients want to invest in the stock market. Since they are passionate about green energy, particularly (DQ,) we decided to create a diverced portfolio of green energy stocks to increase their chance to gain more return for their investment.<br>

We want to create Excell sheet showing total daily volume and yearly return for twelwe stocks for years 2017 and 2018. Daily volume will show how actively a stock is traded, and the yearly return will show the % differance in the price from the beginning of the year to the end of the year. Based on the analysis we want to help our clients to make best decision.<br>

**Method and Results**<br>
****************************
For this kind of data analysis Excell is the best way to go, this will give us a chance to use VBA code to automate the calculations. VBA helps us reduce the chance of errors and time to run the anaylsis, especially if we needed to run it repeatedly.<br>
<br>
First We prepared 2 excell work sheets with 12 stock tickers with their daily starting and ending prices, daily trading volumes and daily low and high prices for years 2017 and 2018.<br>
Then, we initialized an array for all tickers then initialized variables for the starting and ending prices for each ticker and total volumes. Looping through tickers and rows we found Total Valume and total return for year 2017 and 2018. To make the process faster , Instead of using ticker variable for each stock we created a tickerindex variable and it helped us to access the correct index for four different arrays. This refactoring helped the process to run 10 times faster.<br>

Whatever the method is used the result are as follow;<br> 
<br>
**Year 2017**<br>
Despite DQ had the lowest Total Daily Volume it had the highest return of 199.4 %.On the other hand SPWR had highest daily volume yet the return was only 23.1 %. Most successful stoks were DQ, SEDG, ENPH for the year 2017.<br>
<br>
![](https://github.com/4renginy/Stock-Analysis/blob/master/Resources/AllStocks2017.PNG)  
![](https://github.com/4renginy/Stock-Analysis/blob/master/Resources/VBA_Challenge_2017.png)  
**Year 2018**<br> 
<br>
Last years winner DQ has lost 62.6 % of its value in 2018. RUN has the most return and ENPH has the highest daily volume for year 2018.  Year 2018 was not a good year for green energy stocks.<br>
<br>
![](https://github.com/4renginy/Stock-Analysis/blob/master/Resources/AllStocks2018.PNG)  
![](https://github.com/4renginy/Stock-Analysis/blob/master/Resources/VBA_Challenge_2018.png)  
>Looking at those 2 years results comparasan, we can recommend to purchase ENPH, SEDG and RUN.

**Summary** <br>
***********************
Refactoring is intended to improve the design and structure of the code without loosing functinlality. So it helps to make the design cleaner, easy to understand, easy to implement, and easy to maintain. Also it helps to perform faster with less memory usage.<br> 
<br>
Although Refactoring has number of benefits, it is not a good idea to do it if the delivery deadline is near, the process could introduce bugs and there might not be enough time to fix. Some cases cost of refactoring could be higher then rewriting the code from the scratch. Refactoring time consuming so tight scheduled projects should not be refactored.<br>

If the original code is working without any issues and satisfies all the necessities, easy to understand, claer to any code reader, there is no memory issues, refacturing would be waist of time and money.

