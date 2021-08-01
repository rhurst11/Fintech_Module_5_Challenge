# Fintech_Module_5_Challenge


## Software Requirements


## Description:

This project aims to provide two separate financial analysis tools within one jupyter notebook. 

The first tool for financial analysis is a financial planner for emergencies. Users are able to use this tool to visualize their current savings. The members can then allow the program to determine if they have enough reserves for an emergency fund via conditional logic. 
    
The second tool for financial anlysis is a financial planner for retirement. This tool forecasts the performance of a user's retirement portfolio over two time periods: 30 years and 10 years. In order to do this, the tool makes an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations that are integrated into the jupyter notebook program.

    
## Thirty Year Monte Carlo Simulation Analysis: 

There is a 95% chance that the future value of the member's stock and bond portfolio will fall between a range of $167,952.93 and $2,850,171.79.


## Ten Year:

There is a 95% chance that the future value of the member's stock and bond portfolio will fall between a range of $52983.47 and $480169.90.


### Final Question: Will weighting the portfolio more heavily to stocks allow the credit union members to retire after only 10 years?

Answer:

Weighting the portfolio more heavily to stocks will not provide a reliable mechanism for retirement within ten years. 

If the portfolio performed well, and the future value of it was closer to the projected high of roughly $470,532 retirement could be feasible 

However, if the portfolio performs poorly and has a future value closer to the range low of $52,680, the cost of living would most likely consume this retirement fund too quickly to live off of until end of life assuming the user lives in the United States. 




