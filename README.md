# Alaska-UBI-analysis
# Looks at how the Alaska Permanent Fund(a form of a universal basic income in Alaska) impacted violent and property crime rates in the first two years before and after its start year of 1982. 
# This was to test the hypothesis that due to the increase in income and decrease in income inequality, violent and property crime would both reduce. 
# It was also expected property crime would be affected a lot more that the correlation between the explanatory variables would have a much stronger correlation with property crime than violent crime.
# The raw data was created on IPUMS CPS and is stored in the Copy of s165u1u4BUbp (1).csv file and Copy of s133UN01qyLD (2) file.
# The Copy of s165u1u4BUbp (1).csv file carries income data while the Copy of s133UN01qyLD (2) file carries the race data.
# The data cleaning was done twice (once in Python and once in SQL). The reason for this was that I had not learnt SQL when I first did it. 
# The file for the Python data cleaning had most of the initial iterations but the final code was in cleaningandedacode.ipynb.
# Both SQL and Python produced finalcleandata.xlsx after the data was cleaned.
# Exploratory data analysis was also performed on Python.
# crime data.xlsx was also added to the finalcleandata.xlsx table.
# The final code iteration with analysis also can be found at incomeandcrimeslr (4).ipynb.
# Key insights gained:-
# 1) DC is a complete and total outlier because the crime rate(both property and violent) that it significantly skews and subsequently biases the data.
# 2) We have continuously got statistically significant results at the 5% level that, in general, violent and property increases when there is more income. This makes sense for property crime intuitively as more income means more wealth to steal but not violent crime as you would think more income would mean more investment in the police force which would mean fewer criminals get away with their crimes.
# 3) Violent crime goes up with more income inequality(as measured by the Gini coefficient) but property crime goes down. These findings are statistically significant also till the 5% level and for property crime at the 0.1% level also. 
# 4) The only feasible explanation for why this is happening with violent crime is that when income and income inequality increase simultaneously people tend to become violent as an increase in income would mean a better prepared police force(as long as funds are distributed appropriately). 
# 5) An implementation of an universal basic income decreased violent crime by 0.0058 and property crime by 0.1767 incidents for every $1 increase income. 
# 6) Similarly, violent crime went down by 4.4128 and property crime by 34.1578 incidents for every 1 point increase in the Gini coefficient after the implementation of the universal basic income.
