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

# Description:

This assignment explores the temperate climate of the Hawaiian Islands using a combination of Python's SQLAlchemy, Pandas, and Matplotlib libraries. A SQLite ([Hawaii.sqlite](https://github.com/blhawkins/SunAndSurf/blob/master/Resources/hawaii.sqlite)) file containing Oahu and Maui-based weather records was successfully mapped into a Jupyter Notebook. Then, various analyses were performed on the data in order to visualize and draw conclusions regarding percipitation and temperature records over the course of a calendar year.

### [Climate.ipynb](https://github.com/blhawkins/SunAndSurf/blob/master/climate.ipynb)
Components of the climate.ipynb file include:
1. Use of the SQLAlchemy ORM to map the [Hawaii.sqlite](https://github.com/blhawkins/SunAndSurf/blob/master/Resources/hawaii.sqlite) database file into readable Python objects.
2. Use of SQLAlchemy's session function, Python's datetime library, and Pandas to recover precipitation records for the most recent year.
3. Use of Matplotlib to create a bar chart displaying the precipitation records of the most recent year.  
![alt text](https://github.com/blhawkins/SunAndSurf/blob/master/Figures/year_percipitation_records.png 'Bar chart showing percipitation records between August 2016 and August 2017')
4. Use of the Pandas and Numpy libraries to create a table showing summary statistics for the precipitation data.
5. Use of session queries to determine the number of testing centers from which data was reported, as well as the testing center that produced the most measurements. 
6. Use of session queries to determine the maximum, minimum, and average temperatures recorded at the most active testing center.
7. Use of session queries and Pandas to obtain all temperature measurements originating from the most active testing center during the most recent year.
8. Use of Matplotlib to create a histogram modelling the temperature measurements taken at the most active testing center during the most recent year.  
![alt text](https://github.com/blhawkins/SunAndSurf/blob/master/Figures/year_temperature_records.png 'Histogram of temperature records taken at Station USC00519281 between August 2016 and August 2017')
### [Climate.ipynb](https://github.com/blhawkins/SunAndSurf/blob/master/climate.ipynb) (Bonus Analysis)
Additional components of the climate.ipynb file include:
1. Use of session queries, Pandas, and SciPy's ttest_ind function to test whether the average temperatures in December and June are statistically distinct.
2. Use of session queries, Pandas, and MatplotLib to create a bar chart displaying the expected temperature for a hypothetical Hawaiian vacation in early February.  
![alt text](https://github.com/blhawkins/SunAndSurf/blob/master/Figures/trip_temperature_records.png 'Bar chart showing the expected average temperature in early February')
3. Use of session queries, Pandas, MatplotLib, and the datetime library to determine expected temperatures for a range of dates in early February, based on historical data.  
![alt text](https://github.com/blhawkins/SunAndSurf/blob/master/Figures/trip_temperature_normals.png 'Line graph showing expected daily temperatures for a range of dates in early February')