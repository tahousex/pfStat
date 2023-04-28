# pfStat

pfStat: Personal Finance Statistics for Dummies

What is pfStat?

This package is entitled pfStat, and is a small package with a few functions dedicated to helping a user calculate different personal finance metrics. The functions include the ability to derive Returns on Interest, Tax Rates based on Income, Taxable Income and Home Equity, and the purpose behind choosing these kinds of metrics was to emphasize the importance of knowing where one puts their wallet. It goes without being entirely sanctimonious that the dollar does not go as far as it once did, and knowing where one stands amongst their own finances and parameters in the financial world will assist them in making more calculated decisions. 

The Functions:

The taxrate() income receives input from the user income and state tax percentage represented as a decimal percentage (0-1) and gives the user output of a dollar amount of the taxes owed based on the input

The taxableincome() function takes the user income and calculates the taxable income after all deductions and exemptions are subtracted from the income. Deductions being write offs out right, and exemptions being more concrete like a state tax exemption affidavit, and how much was not taxed in the process of that year. This is more applicable to small business owners and resellers due to the fact that many of these people hold tax exemption permits issued by the state in order to curb costs.

The equity() function calculates a user's home or property equity by means of subtracting the sum of All Liens and Remaining Principal on the Mortgage/Loan from the Fair Market Value of the property in question. 

The personalbudget() function recieves a users income and applies the 50-30-20 percent personal budget principle to break down their income into a table of costs labeled by necessities, wants and savings with corresponding values in USD.

The ROI() function does exactly as it is named, the Return on Investment, but based solely on gross income or net income. Given an investment cost and the net income it derives a rough ROI

The timeROI() function does similar to the prior but in a slightly different way, using the final and initial investment values, the number of months and the cost of the investment, the function provides a mixed format output in this form "% 65 over 18 months".

Closing Remarks:

Hopefully some of you may find some utility with this, there are many other financial packages out there of immense utility but, mine is a demonstration that sometimes the best packages are the most applicable ones in subjects like personal finance, statistics, mathematics and overall home economics in a way, keeping expenses and income balanced is key to having some sanity in these recent times.
