# Stock-Analysis
Week 2 project
## Overview of Project:
The purpose of this project is to help my friend, Steve, who has just graudated with a degree in finance.  He is helping his parents make some investments and he wants to look into the sector of green stocks since his parents are passionate about green energy.  Steve has gathered data on stocks and placed the information in an excel spreadsheet and has asked me to help him analyze the value of their return for each year.  

Steve used the tool to evaluate the performance of stocks and has enjoyed using the spreadsheet.  He is wanting to use it for additional stock data for future clients.  In order to do this, the code needs to be refactored in order to include more stock data.

## Results:
The original code ran the analysis on the 2017 stock data in 1.222656 seconds:

![2017_Original_Speed](https://user-images.githubusercontent.com/107599510/179860079-4585cc90-e31e-47e6-a83a-355e0d31e708.png)

The refactored code for 2017 ran in 0.121904 seconds:

![2017_Refactored_Speed](https://user-images.githubusercontent.com/107599510/179860182-dad3bacd-abd3-486a-ad7d-f688f06d5d4d.png)

If we take the seconds and multiply it by 1,000, it helps provide a little better insight into the speed differences.  The 2017 original speed would equate to 1,222.656 while the refactored speed would equate to 121.9038 when both are multiplied by 1,000.  The refactored code is significantly more efficient than the original code.

The original code ran the analysis on the 2018 stock data in 1.132813 seconds:

![2018_Original_Speed](https://user-images.githubusercontent.com/107599510/179860561-a80ae301-dc1c-4301-88e6-c5578bb58f36.png)

The refactored code for 2018 ran in 0.125 seconds:

![2018_Refactored_Speed](https://user-images.githubusercontent.com/107599510/179860806-d95ad25c-be7a-40e0-8c9c-3ddcf303a5e6.png)

Just like for the 2017 numbers, it is easier to see the difference in speed by multiplying the results by 1,000.  For 2018, the original code number would be 1,132.813 while the refactored 2018 number is 125.  The refactored code is significantly more efficient than the original code.

## Summary:

#### What are the advantages or disadvantages of refactoring code?
There are some clear advantages of refactoring code.  In this example, the speed at which the computer was able to provide the same data improved significantly.  This code can also be used in the future for a different set of stocks or a different year.  There may be a more efficient way to run the code by grouping data or eliminating steps in a loop that allow the outcome to achieve the same goal.

As far as disadvantages go, the code can end up being broken and stop working.  It is important to read the code to understand what was happening and to add comments to help you during the refactor process.  It is also very helpful to have good comments from the original coder to assist with refactoring.  


