# Sun And Surf
### Climate Study of Oahu and Maui 🏄🏼🏝


## Contents:
    climate.ipynb
    Resources

## Tools Used:
    SQLAlchemy
    Pandas
    NumPy
    Matplotlib
    Datetime
    SciPy Ind. T-Test

## Description:
A. climate.ipynb

1. Use of the SQLAlchemy ORM to map the Hawaii.sqlite database file (Resources folder) into readable Python objects.
2. Use of SQLAlchemy's session function, Python's datetime library, and Pandas to recover precipitation records for the most recent year.
3. Use of Matplotlib to create a bar chart displaying the precipitation records of the most recent year.
4. Use of the Pandas and Numpy libraries to create a table showing summary statistics for the precipitation data.
5. Use of session queries to determine the number of testing centers from which data was reported, as well as the testing center that produced the most measurements. 
6. Use of session queries to determine the maximum, minimum, and average temperatures recorded at the most active testing center.
7. Use of session queries and Pandas to obtain all temperature measurements originating from the most active testing center during the most recent year.
8. Use of Matplotlib to create a histogram modelling the temperature measurements taken at the most active testing center during the most recent year.

B. climate.ipynb (Bonus Analysis)

1. Use of session queries, Pandas, and SciPy's ttest_ind function to test whether the average temperatures in December and June are statistically distinct.
2. Use of session queries, Pandas, and MatplotLib to create a bar chart displaying the expected temperature for a hypothetical Hawaiian vacation.
3. Use of session queries, Pandas, MatplotLib, and the datetime library to determine expected temperatures for a range of dates, based on historical data.

