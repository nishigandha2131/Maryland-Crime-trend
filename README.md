# Maryland-Crime-trend
This project is done in R using regression model to predict the crime rate in every county of Maryland.

The purpose of this project was to help government, policy or insurance makers to understand what rules or policies to make based on the crime rate 
in that county.

The data is obtained from open Maryland portal : https://opendata.maryland.gov/Public-Safety/Violent-Crime-Property-Crime-by-County-1975-to-Pre/jwfa-fdxs
The data is for 42 years from 1975 to 2017.

The project deals with cleaning of Data and then using the LMER (linear mixed effect regression model) on the data to predctcrime rate.
The equation crime_rate ~ Year + (Year | Jurisdiction) was used. The final result is a map which tells the percentage changes in every couny.
Red color indicates percentage increase and sky blue decrease.

Some of the visualizations are done in Tableau


