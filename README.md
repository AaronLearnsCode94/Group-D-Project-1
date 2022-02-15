# Group-D-Project-1
Group D Project: 1

Key activities:

Q1 Analyse and prepare previous commodities data to current commodities data.

Q2 How to accurately plot and display the data.

Q3 Calculate daily, monthly or yearly (or all) returns of each individuals assigned commodity.

Q4 Combine all data frames to then correlate and plot relations between the commodities.

Q5 Plot closing prices of said commodities and plot accordingly.

Q6 Calculate the moving averages of the commodities and compare performance.

Q7 Overlay Prices of all commodities to see if there is one that outperformed and or underperformed the others.

Key data:

Use day-by–day/week-by-week data for most popular Australian resources

Project purpose:

1) Explore historical performance of the resources

2) Explore their historical relationship and how it changed though time – do correlation matrix

3) Regress/Correlate them on ASX 200/other AU indices to find out which commodities affect ASX the most (can try different day lags)

Summary of activities to do:

1) Do interpolation for missing dates (in case few work days missing)

2) Drop Nan for weekends

3) Multiply all commodity columns by AUD exchange rate

4) Concat all together

5) Calculate % changes

6) Calculate cumlative returns

7) Calculate mean/variuence, other risk measures

8) Do correlation seaborn map

9) Add ratios calculations between commodities

10) Update yahho indeces to match commoditied dataframe and start comparing

11) Charts etc

Key commodities:

Steel, Iron Ore, Metallurgical Coal, Thermal Coal, Gas, Oil, Uranim, Gold, Aluminium, Copper, Nickel, Zinc, Lithium
