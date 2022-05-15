
# Project 1 : S&P Simulation Tool

# Financial Simulation with APIs / Predicting the Future with Monte Carlo Simulations

## Summary  


---

# Instructions 
Our Financial analysis includes the following:


- Collect the Stock and Bond data Using the Alpaca SDK

- Evaluate the data

- Create the Monte Carlo Simulation

- Analyze Portfolio Forecasts

- Forecast Cumulative Returns 

---

## Technologies
see requierement.txt

## Programing and financial libraries
Imports and required libraries and dependencies. 

        import os
        import requests
        import json
        import pandas as pd
        from dotenv import load_dotenv
        import alpaca_trade_api as tradeapi
        from MCForecastTools import MCSimulation

        %matplotlib inline

You will need to create an account with Alpaca(https://alpaca.markets/). in order to get an API ID and Secret Key. (see SAMPLE.env for your dotenv file)

---

## Contributors

Tiago Lopes 
Philip DeNormandie
Dynah Beermann
Bennett Kramer
Drissa Compaore 

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
