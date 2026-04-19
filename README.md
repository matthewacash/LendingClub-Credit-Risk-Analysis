# Lending Club Portfolio Risk and Profitability Analysis

![Dashboard Preview](LendingClub_Dashboard.png)

### Executive Summary
This project identifies the true yield of the Lending Club 2.9M record loan portfolio. I isolated "finished" loan cycles and found that nearly all credit grades (excluding Grade A) resulted in a net loss. 

### Technical Stack
* **Python (Google Colab)**: Data pre-processing and cleaning of 2.9M rows, and data type optimization.
* **MySQL**: Logic testing for delinquency buckets (PAR 30/90).
* **Power BI (DAX)**: Weighted average measures for Default Rate and Net Yield.

### Business Insights
* **Whale Risk**: Identified a 5% increase in default probability for loans over $30,000 compared to standard-size loans, specifically peaking at a 35% default rate for subprime whales. 
* **Negative Yield**: Grades B–G destroy value and show negative yield.
* **Vintage Spikes**: Identified systemic risk leaps in 2016 and 2018.


