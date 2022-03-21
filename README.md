# Unit-5---Financial-Planning-Homework
Unit 5 Homework Task. In this task I have made a financial planner that allows users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money to match an emergency fund. Partially using this information the second task was completed: a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years.

### Notale Libraries Used:
* Pandas
* Dotenv
* MatPlotLib
* Alpaca Trade API

### Please Note:
* main notebook is located in the Starter_Code file in the Instructions Directory
* Couldnt use .barset as i kept getting a http 404 error. Later found out this was due to a change in the alpaca Codebase itself. Substituted this with .bars
* Only the base activities are completed
* framework for Monte Carlo Simulations was provided