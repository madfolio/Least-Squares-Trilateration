# Least-Squares-Trilateration
Trilateration example using least squares method in scipy

## Method
The first file,https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/scipy.optimize.least_squares.ipynb , takes 9 points which have a range to an unknown point.  

The second file, https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/Result%20Using%20Simulated%20Points%20In%20Pandas.ipynb, takes a large number of points, finds the "best" 500 and uses these in the least squares equations. 

Trilateration enables the unknown point to be found. However a since there are a number of samples a non linear least squares method needs to be used to find the solution that has the least error. 






