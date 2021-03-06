# Stock Analysis

What started out as a simple analysis of a particular stock, DQ, for our friend Steve yielded such good results that we decided to expand it to cover several more stock tickers. Taking our code and refactoring it to go beyond just the original target stock, we were able to run the same code to cover 12 possible stock tickers and record their Total Daily Volume and their returns, while also being able to do this for different years with a simple input to a message box. This code should be able to run smoothly across different years beyond the 2017 and 2018 data sets we were given to work with, and could accommodate more stock tickers for tracking as needed so long as they are added to array holding the ticker values. 

## Analysis

When running our new code and entering "2017" in the the prompt, we are greeted with these results:

![Capture 2017](https://github.com/BPeaver/Stock_Analysis/blob/main/Resources/Capture%202017.PNG)

Similarly, if we enter "2018" into the same prompt box when running the code again, it yields the following:

![Capture 2018clear](https://github.com/BPeaver/Stock_Analysis/blob/main/Resources/Capture%202018clear.PNG)

Comparing these two results tells us some information, such as 2017 being a better year on average for stock investments than 2018 which saw the majority of reeturns in the negative. It also lets us see that two particular stocks, ENPH and RUN, were the only stock tickers to have positive returns in both years and could potentially be a good long term investment 

## Summary

So what are the advantages of refactoring code? Well for starters, it allows us to simply and streamline our code to make it easier to read. Minus all the green comment lines, the code is fairly easy to follow. It also allows us to loop through more data easier using For loops, so that even though both sets of data were analyzed at different speeds (less than .9 seconds), they are still analyzed far faster than running individual sets of code for each section of data we want to see. 

The only real disadvantage we could find was that it was labor intensive to write and test the code to ensure it all works properly and loops through accordingly. Rather than writing individual sets of code and simply copying the basic format and tweaking, it took some doing to make sure everything worked accordingly. However, with practice and experience this should become less of an issue.
