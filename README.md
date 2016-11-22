# cuddly-bassoon
Rmarkdown file for the following assignment:
Live Session Unit 11 Assignment

       Due:  November 21, 2016 (Monday)

Go through the electric equipment example. 

More examples of forecasting!
Code to load data:
library(fpp) #fpp package must be installed first
data(ukcars)

Plot the time series. Can you identify seasonal fluctuations and/or a trend? 
There is a seasonal trend of peaks and valleys at a constant rate.

Use a classical decomposition to calculate the trend-cycle and seasonal indices. 

Do the results support the graphical interpretation from part (a)? 
Compute and plot the seasonally adjusted data. 
Change one observation to be an outlier (e.g., add 500 to one observation), and recompute the seasonally adjusted data. What is the effect of the outlier? 
Does it make any difference if the outlier is near the end rather than in the middle of the time series? 
Use STL to decompose the series. 

 Deliverable is a link to R Markdown file on GitHub.
