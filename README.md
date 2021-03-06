# Futures_Portfolio_Project
Project Goals:
1. Collect end-of-day (EOD) historical data from Quandl on the most liquid futures markets that trade on exchanges around the world.
2. Also collect EOD foreign exchange (FX), interest rate, and weekly Commitment Of Traders (COT) data that will be used later for analysis.
3. Organize data into 5 tables and write to a SQLite database.
![Alt text](DB_Schema.png?raw=true "Title")
4. Construct continuous price series that are currency adjusted (for non USD markets).
5. Explore predictive factors - momentum, value, carry, term structure, etc.
6. Build multi factor model
7. Dynamically optimize portfolio for efficient allocation of risk within capital constraints.
8. Schedule DB Update and portfolio optimization functions for after market hours every day.
9. Write to TWS_API (Interactive Brokers) and execute into Sim account - new position entry orders, rebalance, rollovers etc.
