# Fintech_Module_5_Challenge


## Software Requirements:

  Python -- version 3.7.10,
  Conda -- version 4.10.3,
  Jupyter Lab -- version 3.0.14
  
  
  Libraries:
  Pandas,
  JSON,
  OS,
  MCForecastTools,
  Dotenv,
  Alpaca Trade API


## Description:

This project aims to provide two separate financial analysis tools within one jupyter notebook. 

The first tool for financial analysis is a financial planner for emergencies. Users are able to use this tool to visualize their current savings. The members can then allow the program to determine if they have enough reserves for an emergency fund via conditional logic. 
    
The second tool for financial anlysis is a financial planner for retirement. This tool forecasts the performance of a user's retirement portfolio over two time periods: 30 years and 10 years. In order to do this, the tool makes an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations that are integrated into the jupyter notebook program.

    
## Thirty Year Monte Carlo Simulation Analysis: 

![alt text](https://github.com/rhurst11/Fintech_Module_5_Challenge/blob/main/Screenshots_Mod_5/30_yr_mod_5_MC.png)

![alt text](https://github.com/rhurst11/Fintech_Module_5_Challenge/blob/main/Screenshots_Mod_5/30_yr_mod_5_CI.png)

### Question: What are the lower and upper bounds for the expected value of the portfolio in 30 years with a 95% confidence interval? 

Answer: 

There is a 95% chance that the future value of the member's stock and bond portfolio will fall between a range of $167,952.93 and $2,850,171.79.


## Ten Year:

![alt text](https://github.com/rhurst11/Fintech_Module_5_Challenge/blob/main/Screenshots_Mod_5/10_yr_mod_5_MC.png)

![alt text](https://github.com/rhurst11/Fintech_Module_5_Challenge/blob/main/Screenshots_Mod_5/10_yr_mod_5_CI.png)

### Question: What are the lower and upper bounds for the expected value of the portfolio in ten years (with the new weights) with a 95% confidence interval? 

Answer: 

There is a 95% chance that the future value of the member's stock and bond portfolio will fall between a range of $52,983.47 and $480,169.90.


### Final Question: Will weighting the portfolio more heavily to stocks allow the credit union members to retire after only 10 years?

Answer:

Weighting the portfolio more heavily to stocks will not provide a reliable mechanism for retirement within ten years. 

If the portfolio performed well, and the future value of it was closer to the projected high of roughly $480,532 retirement could be feasible 

However, if the portfolio performs poorly and has a future value closer to the range low of $52,680, the cost of living would most likely consume this retirement fund too quickly to live off of until end of life assuming the user lives in the United States. 




