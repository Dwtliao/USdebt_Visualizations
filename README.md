# USdebt_Visualizations
### Charts of US Fed Debt: 
R Studio using **ggplot2** library made interactive with library **plotly** (now free!)
&amp; www.bertfier.com matrix &amp; **Tableau**

Quarterly debt of US Fed from 1970 to 2016 is used for interactive R charts using **ggplot2** library

http://bertifier.com/ is a very interesting visualization tool that compresses time series data very nicely
The US government has ran a Deficit budget almost every year since the late 1960s except for a brief 4 years from 1998-2001. As spending exceeds receipts continuously, the difference is made up by borrowing more and thus the national debt increases each year as the principal on the debt can never be reduced unless the annual budget produces a surplus.  Receipts and Spending are colored here using a greyscale and the black bars show when Spending became extreme relative to past years, from Year 2000 forward.  The choice of greyscale for first 2 rows is to setup the better story below. The blue vs red color encoding for Net Budget and Spend(-), is done not on absolute values, but relative to the baseline when the minimum & maximum of each row’s data is given.  This shows the Budget deficits in the 1960s-1980s years were small relative to what has happened since 2003 when the Budget values start becoming red.  Years 2009-2012 have the largest red bars because the budget deficit after 2008’s  financial crisis was so large relative to other years.  But this is precisely what has elevated the national debt to rise to such levels so quickly.  The Bertifier Matrix is doing a relative value comparison of the Net Budget as it flips between + or - numbers and identifies trend changes at a particular point in time.  The Bertifier matrix makes very economical  horizontal use of chart width as many years are compressed together and allowing the removing of lines between each year column which allows the eye to see the visual patterns more easily.  Our national debt was still manageable before 2003 but has exploded in the last 13 years and projections to 2021 keep the national federal budget very much in the ‘red’.

#### US Debt Interest Rate Payments - Future Obligations if interest rates change
One of my main interest in this US Public Debt story is increasing adverse effect of higher interest rates on the Interest Rate Payments.  The US Federal Government has not been able to pay down even a little bit of the principal of the total debt as one must have a budget surplus to have the extra dollars to pay down the principal.
I created my own projections of future interest rate payments using the White House 2017 Budget’s estimated deficit projections through year 2020 and assumed a constant annual modest deficit for years 2021 to 2035 and used 5 very modest interest rate scenarios using interest rates of 2.25% to 5.0%.  The Fiscal Year 2015 White House numbers show an approximate interest rate payment of about 2.2% for year 2015 and that was chosen as the minimum constant interest rate.  A upper limit of 5.0% is quite a reasonable assumption given historical interest rates from the past.  Then the total interest payments under these 5 interest rate scenarios were explored and analyzed.  

as written about in a length “opinion” piece that was the front page article in Time magazine (http://time.com/4293630/in-the-latest-issue-67/).
And then go get the economic data to explore and support the story.  
The Time article can be summarized as: the US government owes $13.9 trillion in debt and each of us would need to pay $42,998.12 to pay it off.   I then found much of the exploratory data to support the story through the WhiteHouse.gov web site (https://www.whitehouse.gov/omb/budget/Historicals ) 
and the US Government Publishing Office (https://www.gpo.gov/fdsys/browse/collection.action?collectionCode=BUDGET&browsePath=Fiscal+Year+2017&searchPath=Fiscal+Year+2017&leafLevelBrowse=false&isCollapsed=false&isOpen=true&packageid=BUDGET-2017-TAB&ycord=300 ).
