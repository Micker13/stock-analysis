# 2017-2018 Stock Analysis for Portfolio

Worksheet and code to analyze historical stock information for 12 selected companies

The basis for this workflow and project was to perform a satisfactory high level analysis of 12 specific corporations on our clients behalf.  Data was retrieved for all companies over 2017 and 2018 to provide historical performance data for each.  The summary table will include a total daily volume for each company along with an overall percent gain or loss of the fund.  

Company performance

At a high level, 2017 was a strong year for the majority of the companies with over 100% gains being shown in 4 out of 12 funds.  Only one company, TERP, displayed weaker growth during this market time period.  2018 was a more difficult year with only two positive performance and extreme downfalls in the majority of other funds.  TERP again showed no growth and is unlikely to be a profitable company in the long term.  However, companies RUN and ENPH continued to make large strides and had some of the largest total trading volume across the market.

![image](https://user-images.githubusercontent.com/107594247/176572146-c8cfac94-893d-4027-ab91-0bde003b7628.png)

![image](https://user-images.githubusercontent.com/107594247/176572184-4c7e9e74-3c1c-4b3d-bee6-ab0385405dc0.png)

However, all of these outcomes requires further analysis, using only a single pair of data points for comparison (start compared to end of year) is not sufficient to show company performance.  Interyear data (which is available here) should be compared to show if there were possible opportunities within the year that this analysis does not show.  As a possible example, if TERP had a mid year run of +50% and only fell in december, this is worth analysis and would not be visible with the current table.


Coding Background

The initial analysis done for this dataset was done with a more complex coding setup based on identifying problems as they emerged.  After the work was completed, we were able to significantly reduce runtime by simplifying looping and limiting repetitive work.  Overall time dropped from ~.5 seconds per analysis to .07/.06 seconds.  In overall efficiency, the current code present in the file is almost 90% faster speed.  This is a standard way to reverse engineer your own code and ensure it is performing as intended and at peak levels.  The only cases this should not be done is when time is more critical or there is no need to maximize speed of results. 

