# Stock-Price-Currency-Converter
This program shows Turkish stock prices in USD terms over time.

I am developing this program to better understand the dollar values of Turkish companies.  The dollar value of many stocks in developing countries like Turkey are hard to grasp because their values are listed in their own currencies and these currencies are often volatile.  For example many Turkish stock prices are rising in TRY term over the last few years while falling steeply in USD terms.  This is due to the rapid depreciation of the turkish lira (TRY).

The program currently requires a Yahoo Finance link to the history page of the stock, the currency the stock is listed in, and the period of time it is supposed to get data for.  The options for the period of time are the options given by Yahoo finance (3_M, 6_M, 1_Y, 5_Y, MAX).  It outputs a graph that plots both the local currency and the USD value graph of the said stock for that period on the same figure using 2 Y-axes.

This program is currently written in Python using Jupyter Notebook.  It uses Forex API to access past exchange rates and Yahoo Finance to access past stock values.
It will be developed further into a single function, and the goal is to make it able to function with any stock that can be found via Yahoo Finance.
