# Airfare Prediction
The motivation for this project is that several new airports have opened in major cities (at the time of this data collection in 1996), and a major airline wants to predict what fare prices for these new flights could be. 

The dataset used in this model is located in the Airfares.xls file. It contains real data that was collected for the third quarter of 1996 and is made up of the following predictors and response:
- S_CODE = Starting airport's code
- S_CITY = Starting city
- E_CODE = Ending airport's code
- E_CITY = Ending city
- COUPON = Average number of coupons (a one-coupon flight is a non-stop flight, a two-coupon flight is a one stop flight, etc.) for that route
- NEW = Number of new carriers entering that route between Q3-96 and Q2-97
- VACATION = Whether a vacation route (Yes) or not (No)
- SW = Whether Southwest Airlines serves that route (Yes) or not (No)
- HI = Herfindel Index - measure of market concentration
- S_INCOME = Starting city's average personal income
- E_INCOME = Ending city's average personal income
- S_POP = Starting city's population
- E_POP = Ending city's population
- SLOT = Whether either endpoint airport is slot controlled or not; this is a measure of airport congestion
- GATE = Whether either endpoint airport has gate constraints or not; this is another measure of airport congestion
- DISTANCE = Distance between two endpoint airports in miles
- PAX = Number of passengers on that route during period of data collection
- FARE (response) = Average fare on that route
