# finance-utils
A tool to visualize, analyze and prioritize between financial assets

## Plan

- Figure out way to fetch daily prices/arithmetic returns for all Nordic & American stocks & indices
- Store these in a database
- Automate daily retrieval of these prices

- Set up a front-end where users can input their holdings
- The user shall be able to get financial metrics for their holdings, time series etc
- The user shall be able to access the database, sort it by different metrics

- Implement and deploy machine learning algorithms to predict stock prices and other interesting metrics that can be useful to the user


## Tech stack

- Retrieval & Database insertion (scripts): Python (pandas, numpy, SQLalchemy)
- Front-end & Back-end & Database querying: React & Node.js
    - Should call python scripts
- Machine learning algorithms:
    - Developed with python
    - Eventual deep learning models should be compiled with c++
